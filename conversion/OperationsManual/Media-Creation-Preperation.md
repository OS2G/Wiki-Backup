This page will contain all the steps and tools necessary to
create/prepare media such as photos, graphics, and videos (inc. Audio)
for anything (OS)<sub>2</sub>G related.

# Programs & Tools

As this is a club dedicated to open source, we try and do everything
open source. The following is a list of tools and programs that are open
source that can be used to make media.

## Audio

  - [Audacity](https://www.audacityteam.org/) (Audio editing)
  - [FFmpeg](https://www.ffmpeg.org/) (Video/Audio trans-code and codec
    software)

## Video

  - [Kdenlive](https://kdenlive.org/) (Video editor)
  - [Blender](https://www.blender.org/) (3d animation & modeling)
  - [Natron](https://natron.fr/) (Post Compositing (think After
    Effects))
  - [FFmpeg](https://www.ffmpeg.org/) (Video/Audio trans-code and codec
    software)

## Graphics/Photos

  - [GIMP](https://www.gimp.org/) (GNU Image Manipulation Program, AKA:
    Image editor (like Photoshop))
  - [Krita](https://krita.org/en/) (Drawing software (like Illustrator &
    Paint Tool SAI))
  - [LaTeX](https://www.latex-project.org/) (Document Preparation &
    Typesetting System)

# Graphics Creation / Image Editing

This part of the guide will aid in editing images and creating media to
fit website content, videos, and anything else where such content would
be useful.

## Lens Correction

Images taken with fisheye lenses (like a GoPro where there is lens of
distortion) can be corrected but take caution, as this often causes the
main objects of the image (those in the middle) to be oddly larger than
the rest of the image’s content. In other words, if you decided to apply
lens correction to lens distorted images, play around with the settings
to make sure the corrected image does not look worse than the original
image. This is also why partly correcting a distorted image may be
better than fully correcting an image.

<small>*Examples & settings coming soon*</small>

## For the Website

Any graphics with text should utilize the Ubuntu font as that is what we
have thus far adopted.

Images used in the carousel (on the home page) should be 16:9 or a
similar ratio to fit the rest of the images, this way, the carousel
doesn’t resize to fit the image. Crop using the Rule of Thirds, where
most heads or main content should fit into the top third of the grid, or
on the line. This way, the images wont contain much empty space.

Images used elsewhere on the site should be cropped according to how
they are to fit the site’s content. IE: If it will be in a side column,
make sure it fits the original width of the column as to not make it
oddly larger or smaller than the content.

<small>*Examples & settings coming soon*</small>

## For Videos

Images can be created in GIMP and should generally contain the
(OS)<sub>2</sub>G logo as well as the content of the video and the main
speaker. White background is what is typically used for the intro
graphics. The image should be the same resolution as the video itself
(usually 1920x1080 16:9). An ending graphic will contain the logo with a
website URL on a black background.

<small>*Templates & examples coming soon*</small>

## Other Tools

### LaTeX

While not necessarily meant for graphics creation, with enough
formatting and the right templates, many of the same things that you can
do in GIMP to make a title slide or similar graphic can be made in
LaTeX, and with a possibly better, more consistent template. That said,
it is not user friendly and has a learning curve. For a beginning user,
and for more general graphics creation and image editing, I would
definitely recommend using GIMP.

### Krita

If you draw, this is for you, especially if you have a drawing tablet
with pen. This is a very good Paint Tool SAI and Adobe Illustrator
equivalent. And it’s free.

# Audio Editing

Audio editing will mostly consist of taking audio clips (either recorded
or from video) and modifying them with equalization, filters,
compressors, and more to achieve a better, or a desired sound outcome.
There are many tools that can do this such as Sony Vegas, Adobe
Audition, and more importantly, Audacity.

<small>*More content coming soon*</small>

# Video Editing

While 3D animation and post-production compositing would be pretty
awesome for (OS)<sub>2</sub>G, it’s not something we might ever need to
use, especially on a general basis. Because of this, this guide will
simply go into the basics of video editing.

Some of the most popular video editing software known to many people are
things like Adobe Premiere Pro, Apple Final Cut Pro, Windows Movie
Maker, iMovie, and so on. Sadly, none of those option are opensource, or
free necessarily (Windows movie maker is, but it’s also not a great
tool). At UNL, Adobe creative suite is offered to students free of
charge which is nice, but it won’t last forever. So, in honor of this
group’s principles (open source) and because it’s the most affordable
option, the recommended tool to use is Kdenlive, and this guide will
cover it from start to finish on how to get set up with it, as well as
edit, render, and post the final video.

## Kdenlive

Kdenlive is one of the best, most feature rich open source and free
video editors available. It’s also cross-platform. More info about it
can be found [here](https://userbase.kde.org/Kdenlive).

### Installation

Installation varies on the OS, basic instructions can be found on the
[Kdenlive download page](https://kdenlive.org/download/).

**Windows:** On Windows, the instructions are slightly different than
provided by the site due to some compatibility issues between the
current version of FFmpeg and Kdenlive. Using the instructions provided
by their site will cause Kdenlive to not be able to recognize the
files/codecs necessary to be able to render in the x264 MP4 format. To
rememdy this, simply use the [3.4.1 build of
FFmpeg](https://ffmpeg.zeranoe.com/builds/win64/shared/ffmpeg-3.4.1-win64-shared.zip),
rather than their recommended build. All other instructions are the
same.

### Notes about Kdenlive

  - Kdenlive has a lot of dependencies on the KDE desktop environment,
    meaning it works best on KDE based systems.
  - It has been known to be unstable in one way or another on a number
    of platforms depending on the setup. Sometimes, there are no issues
    at all, other times, it’s almost unusable.
  - Because of its possibility of crashing, save often. And I mean all
    the time, especially before big changes, addition of effects, etc.
    The worst thing that can happen to a creator is losing his/her work.
  - Even with a very powerful computer, it may lag when playing back
    video, especially with effects on it. It helps to set up a proxy
    clip system (more on this later).
  - If you have programming experience and some free time, please do
    contribute to their project to make it better and more comparable
    (mostly in user-friendliness and stability) to Adobe Premier Pro and
    Apple Final Cut.

<small>*More content coming soon*</small>
