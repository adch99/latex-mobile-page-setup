# LaTeX For Mobile

It is not a surprising fact that most
people find it hard to read and navigate a LaTeX document when on
the phone. LaTeX defaults are designed for printed paper and when
viewed on phone, people run into these issues:

* The large paper size leads to very small font size when
  the page is viewed as a whole in portrait mode.

* Landscape mode requires that the phone be held horizontally
  which is usually inconvenient and requires a lot of scrolling.

* Many a times, one has to zoom into a small part of the
  document and then move horizontally following the line.
  This makes navigation a headache.

So let's try and produce a version of the document suited for mobile
viewing perhaps? Reading ought to be easy and natural, the design of
the document should get out of the way and let us concentrate on the
content. Hence, I present to you this format. The template.xml file
included with this, will allow you to easily switch between compiling
for desktop and mobile viewers. How hard is it to just compile twice
and put out two files instead of one, if it affords the viewer a
better experience and correspondingly increases the chances your
document will be read properly?

## Instructions
If you have a `.tex` file which you want to compile for mobile viewing:

1. Download this repository or even just the `template.xml` file.
2. Create a copy of the `template.xml` file.
3. Copy and paste the preamble from your existing file into this copy.
4. Copy and paste the main document part from the existing file into the
  copy.
5. Save and compile this new file.

If you thought that the above instructions were too simple, then
congratulations! You have realised an important thing: *It's not that
hard to do this*.