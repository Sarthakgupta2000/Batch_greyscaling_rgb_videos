# Batch_greyscaling_rgb_videos
Converts multiple rgb to greyscale using mp4 video codec(other codecs also available) using openCV

```
Batch convert videos to greyscale .
Install dependencies:
  pip install pillow docopt
Note: If you do not provide an output path, the generated files will be saved
in a folder named "Converted"
Usage:
  greyscale.py <in_path> [<out_path>]
  greyscale.py -h | --help
  greyscale.py --version
Arguments:
  <in_path>   Input directory
  <out_path>  Output directory [default: ./Converted]
Options:
  -h, --help  Show this help screen.
  --version     Show version.
```
