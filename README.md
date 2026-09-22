# CART346-OSaD

## One-Sound-a Day 

For CART 346 Digital Sound I, you are expected to record, generate, or produce one sound or patch per day throughout the term. These media objects will respond to concepts, techniques, and aesthetic questions addressed in class. Depending on the point in the term, the sound or patches will focus on different aspects of digital sound techniques.

You will submit five sounds or patches per week, over ten weeks, for a total of 50 media objects.

Weekly submissions are due Mondays at 23:59, the day before class.

Fork this repository to your GitHub account (instead of download it) and clone it into your computer.



In the files submitted, always use the following file structure:

```
CXX-SYY-filename.fileextension
```

where XX is the week number, YY is the media object number, and the file extension the corresponding extension of the file.

The two files included in folder `C01` are examples of a first week’s submission.

```
C01-S01-wrapping-paper.wav
C01-S02-tapping-glass_FAV.wav
```

Indicate your favorite patch of the week by including `_FAV` in the filename. For example: `C01-S02-tapping-glass_FAV.wav`. Remember to never use spaces in filenames.

Enjoy!

### Week 01—Record something you would normally ignore

This week is about the sounds you've trained yourself to tune out (e.g., the fridge hum, the ventilation, the elevator, a fluorescent light buzz, footsteps on a stair, a zipper, or the room tone of wherever you happen to be). Schafer would call most of these “ground”: sound that stays in the background until you deliberately listen for it. That's the exercise: not finding something rare, but noticing something ordinary.

Within that, though, don't just grab the first background hum you notice. Listen for ones that have some character once you isolate them. For example, the rattle of utensils in a pan, the scrape of a spoon on a nonstick surface, a lid settling onto a pot, keys shifting in a pocket. These are small, ignorable sounds that turn out to have real texture, pitch, or rhythm once you actually listen to them on their own.

Record five of these, in five different moments or locations. Each should be a close, isolated recording of just that sound — evidence of attentive listening with a microphone, not a general room recording it happens to be audible in. Your phone as a recorder is fine, but if you have a better microphone and recorder, use them. Keep each clip short, somewhere between 2 and 15 seconds.

For each one, ask yourself: what did you have to do to hear this in isolation? Wait for something else to stop? Get closer? How close? The questions, and the experimentation it takes to land on a good take, matter more than the recording itself this week.

Once you have your five sounds, here's how to prepare and submit them:

1. **Import** all five recordings into a new Reaper project.
2. **Trim** the beginning and end of each sound: cut dead air and handling noise, keep the sound itself intact.
3. **Export** each one individually as a `.wav` file at 44.1 kHz, 16-bit.
4. **Rename** each exported file following the structure above (`C01-S01-filename.wav` through `C01-S05-filename.wav`), and add `_FAV` to your favorite.
5. **Commit** the five files to your local repository, then **push** to GitHub. New to Git? Follow [GitHub's Getting Started with Git guide](https://docs.github.com/en/get-started/learning-to-code/getting-started-with-git): it covers exactly this workflow.
6. **Verify**: reload your repository's page on GitHub and confirm all your files are there.


7. If you get an error to "RPC failed; HTTP 400 curl 22 The requested URL returned error:400" or similar, you may want to increase the HTTP buffer. Run this in the VS Code terminal (or any terminal) inside the repo, then push again: 

```
git config http.postBuffer 524288000
git push
```