## make_title.py ##
On a site I administer, I often receive posting information that has sentences in all uppercase. This lets me copy each sentence from the source, and expand it into my browser after passing through Python's title() function.

The snippet itself is: 

#!/bin/bash
pbpaste | /Users/parlarjb/bin/make_title.py
