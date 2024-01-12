# gstreamer_intro
gstreamer python tutorial 

## Install gstreamer on MacOS
The easiest way to install gstreamer on MacOS is to use Homebrew. 

Update Homebrew:

```bash
brew update
```

Install gstreamer:

```bash
brew install gstreamer gst-plugins-base gst-plugins-good
```

## Test gstreamer installation


The gst-launch-1.0 command is a tool that builds and runs basic GStreamer pipelines. 
| Command | Description |
|---------|-------------|
| -v      | The optional parameter enables verbose output,printing information about the pipeline as it runs. |
| videotestsrc | The videotestsrc element generates a test video stream. |
| autovideosink | The autovideosink element automatically detects and uses the best available video sink. |

```bash
gst-launch-1.0 -v videotestsrc ! autovideosink
```
