# ARToolkit NFT Utilities: genTexData

## Purpose

genTexData performs training of NFT datasets from a supplied JPEG-format source image.

## Usage

<pre>
./genTexData <filename>
    -level=n
         (n is an integer in range 0 (few) to 4 (many). Default 2.'
    -sd_thresh=<sd_thresh>
    -max_thresh=<max_thresh>
    -min_thresh=<min_thresh>
    -leveli=n
         (n is an integer in range 0 (few) to 3 (many). Default 1.'
    -feature_density=<feature_density>
    -dpi=<dpi>
    -max_dpi=<max_dpi>
    -min_dpi=<min_dpi>
    -background
         Run in background, i.e. as daemon detached from controlling terminal. (Mac OS X and Linux only.)
    -log=<path>
    -loglevel=x
         x is one of: DEBUG, INFO, WARN, ERROR. Default is INFO.
    -exitcode=<path>
    --help -h -?  Display this help
</pre>

## Operating example

### Exit codes
<pre>
E_NO_ERROR = 0
E_BAD_PARAMETER = 64
E_INPUT_DATA_ERROR = 65
E_USER_INPUT_CANCELLED = 66
E_BACKGROUND_OPERATION_UNSUPPORTED = 69
E_DATA_PROCESSING_ERROR = 70
E_UNABLE_TO_DETACH_FROM_CONTROLLING_TERMINAL = 71
E_GENERIC_ERROR = 255
</pre>

See [Training ARToolKit NFT to a new surface][1]

[1]: /Training_ARToolKit_NFT_to_a_new_surface