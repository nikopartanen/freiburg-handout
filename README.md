# Handout for Niko's presentation in Freiburg Workshop at 20.07.2016

This handout discusses few important topics which I think are not addressed well enough in our current workflows. There are of course gazillion thing one could pick up, but I selected these two as they are relevant right now and probably deserve more attention.

- Keeping track of related session files (multiple audio, multiple video)
- Citing individual resources in the corpora (from practical point of view)

This document can be read [here](https://nikopartanen.github.io/freiburg-handout/) and the PDF file available [here](https://nikopartanen.github.io/freiburg-handout/partanen-freiburg-handout.pdf). Although I'm very fond of making research reproducible, this handout totally is not. There are some bells and whistles which one probably can set up anywhere, but at the moment it also needs access to our corpus files. However, it is not unrealistic at all to refer directly to archived items so in principle this local access would not be necessary.

The handout is also nice example from the working method where one can produce good looking PDF and HTML from the same source document. This demands some special attention to the ways how PDF output gets rendered through LaTeX and HTML needs some custom CSS to accomplish something similar, but this is often more a detail than a real problem.

Of course in some cases one probably would need to split the PDF and HTML versions from one another, as HTML would allow very easily much more interactive maps and playable sound and video, which just doesn't work like that in PDF. In principle PDF could contain links to these elements though.

### Outline

- Workflow descriptions often start with how to segment and transcribe, but there is some new work between recording and transcribing
- This post-processing workphase is time intensive and demands very specific skills. Video editing is complicated task to learn, and audio editing / mixing is not any easier. 
- There is talk about how to cite corpora, but I'm most interested about how to do this in practice with needed exactness
- First image shows a result of one recording session (although there are still more photographs which are now ignored besides portraits which are arranged by speaker)
- Not all of these audio files are the most useful now, for example the boompole was bit too windy, but the sound quality is still nice from two lapel mics used
- Marina has one Edirol + Lapel combination, Sasha has the other
- It is obvious while listening which is which, but currently we don't store this information in machine readable format
- Go to XML snippet
- This shows Final Cut Pro X export format, or a snippet from it. It just exemplifies a bit what is going on there.
- The point is that the files we record go together in complicated way, and the file we actually work with is just combination of these files
- Should we also archive these files? Of course, but should we also develop tools to extract wanted information from them?
- Next image
- This is now FCPX view, here one can adjust audio and cut the video, but for example with audio editing one would probably want to use more sophisticated tools. Should the tracks which are more quiet than others be amplified? How to document how that was done?
- There are different units inside this recording now, but we keep it as one
- How do we keep track of these?
- Next image
- This is one possibility and very easy to create
- Video as a tool of meta-documentation
- Second topic: citation
- Go to Bibtex snippet
- Normal practice (I guess?)
- Corpus versions
- Continuous change with spoken data
- Next image
- Use of ID's to cite exact units
- Often I would want more context in the citation
- At least our corpus contains lots of data which has sources which are more complex
- For example, original publishers etc have to mentioned
- Next citation
- Click the link
- Automatic generation of these necessary!
- Tsammalex example
- Maybe this is enough?