# Coding 2 | MUST 4707

## Creating Custom Objects with Properites

In this assignment you will update the file `script.js` and commit it to your assignment repository. Your updated version of `script.js` will have a new object defined that contains a wide range of information on a song. Inside of your song object will be another "nested" object that contains the artist's information.

### Song Research

1. Pick a song you like and look up the following information. Save it for later.
   - title
   - album that the song appears on
   - artist:
     - name
     - instrument
     - birthdate
   - duration (convert it to seconds!)
   - genre
   - label
   - songwriter
   - producer

### Accessing Assignment Template

1. Follow the provided link to the GitHub classroom assignment.
2. You may need to login to your GitHub account.
3. GitHub will duplicate the assignment template, this may take a minute. Refresh the page after a moment, and you should see a link taking you to your assignment repository. This is where you will complete and submit your assignment.

### Coding

You can either download `script.js` to work on it:

- On the respository page you can click on the green code button and click Download Zip.
- Find `script.js`.
- Make Changes: Edit the file in your text editor.
- Click the + icon to upload the file when you are done.

or edit it on the GitHub website.

- Click on `script.js'
- Click the pencil icon (Edit this file) in the upper right corner of the file view.
- Make Changes: Edit the file in the web editor.
- Commit the Changes: Scroll down to the "Commit changes" section. Provide a brief description of your changes in the commit message box.

Either way, Your code will go between the two comments:

```
//↓↓↓↓↓↓↓↓↓↓↓↓YOUR CODE goes below here↓↓↓↓↓↓↓↓↓↓↓↓
```

_this is where you will type your code!_

```
//↑↑↑↑↑↑↑↑↑↑YOUR CODE goes above here↑↑↑↑↑↑↑↑↑↑
//Do not edit below this comment!
module.exports = song; //This allows for auto-testing on Git-Hub classroom.
```

**It is important that you do not change or delete the line of code:** `module.exports = song;`

---

1. In `script.js` declare a new `const` called `song`.
2. Assign to `song` an object `{}`
3. This object should contain the following information:

| property     | info                                                     |
| ------------ | -------------------------------------------------------- |
| `title`      | the song title                                           |
| `album`      | the album that the song appears on                       |
| `artist`     | info about the artist inside a nested object containing: |
| `(artist)`   | `name`                                                   |
| `(artist)`   | `instrument`                                             |
| `(artist)`   | `birthdate`                                              |
| `duration`   | length of the songs in seconds (must be a number!)       |
| `genre`      | genre of the song                                        |
| `label`      | label that released the song                             |
| `songwriter` | songwriter credits                                       |
| `producer`   | producer credtis                                         |

**Your property names must match exactly with the ones listed above.**
For example:
`song.title` will return whatever the name of your song is.
`song.duration` will return a number that is equal the duration of your song in seconds.
`song.artist` will return an object with its own properties
`song.artist.name` will return the name of the artist.

### Submission (Commit)

1. Upload your updated `script.js` to the git by uploading the file or saving the changes you made in the browser.

### Grading Criteria

Your code contained in `script.js` will be auto-graded by GitHub classroom on the following 15 criteria. You must meet all 15 points to pass this assignment.

1. Song object exists
2. Your song object is an object
3. Song object has a property called 'name'
4. Song object has a property called 'album'
5. Song object has a property called 'artist'
6. Song object has a property called 'duration'
7. The property 'duration' is a number
8. Song object has a property called 'genre'
9. Song object has a property called 'label'
10. Song object has a property called 'songwriter'
11. Song object has a property called 'producer'
12. The property 'artist' is an object
13. Artist property has its own property called 'name'
14. Artist property has its own property called 'instrument'
15. Artist property has its own property called 'birthdate'

### Submission and Auto-grading

After committing

1. Check Actions Tab: Navigate to the "Actions" tab in your repository. This section shows the workflow runs, including autograding.
2. View Autograding Results: Click on the specific workflow run associated with your submission. **This will be the name of your last commit.** Here, you can see the details of the autograding process.
3. Review Output: Look for any output or logs from the autograding workflow to understand your submission's performance and any errors. This will be
   - below classroom.yml you will see a button called "Autograding". Click on that.
   - You see a ton of information on this page, scroll around until you find something that looks like the text below. This will tell you what tests you have passed (✓), and what ones you have failed (✕).
4. **Resubmit until it is passes all tests!**

Autograding Log Example:

```
    Song Object Created
      ✓ Song object exists (3 ms)
      ✓ 'Song' is an object (1 ms)
    Song Object Properties
      ✓ Song object has a property called 'name' (1 ms)
      ✓ Song object has a property called 'album' (1 ms)
      ✓ Song object has a property called 'artist'
      ✕ Song object has a property called 'duration' (2 ms)
      ✕ The property 'duration' is a number
      ✕ Song object has a property called 'genre' (1 ms)
      ✓ Song object has a property called 'label'
      ✕ Song object has a property called 'songwriter' (1 ms)
      ✕ Song object has a property called 'producer' (1 ms)
    Nested Artist object as proptery
      ✓ The property 'artist' is an object (1 ms)
      ✕ Artist property has its property called 'name'
      ✕ Artist property has its property called 'instrument'
      ✕ Artist property has its property called 'birthdate' (1 ms)
```
