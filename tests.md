on new server host is now 127.0.0.1



WORKING:
curl -X POST -F 'url=https://iiif.itatti.harvard.edu/iiif/2/yashiro!letters-jp!letter_001.pdf/full/full/0/default.jpg' http://vision.artresearch.net:8888/search

WORKING
curl -X POST -d 'url=https://iiif.artresearch.net/iiif/2/zeri!151200%21150872_g.jpg/full/full/0/default.jpg' http://vision.artresearch.net:8888/search


https://ids.lib.harvard.edu/ids/iiif/44405790/full/full/0/native.jpg


403 FORBIDDEN
curl -X POST -F 'url=https://ids.lib.harvard.edu/ids/iiif/44405790/full/full/0/native.jpg' http://vision.artresearch.net:8888/search

WORKING:
curl -X POST -F 'url=https://iiif.itatti.harvard.edu/iiif/2/yashiro!32044138547039_02.jpg/full/!700,700/0/default.jpg' http://vision.artresearch.net:8888/search


curl -X POST -A 'Mozilla/5.0 (X11; Linux x86_64; rv:30.0) Gecko/20100101 Firefox/30.0' -F 'url=https://ids.lib.harvard.edu/ids/iiif/44405790/full/800,/0/native.jpg' http://vision.artresearch.net:8888/search
