# xview

Download the data
Labels
Label files are small and available for direct download. When your download has finished, verify the file integrity using the SHA1 hashes given for the respective file:

xView3 labels

train.csv (11 MB)
SHA1: 98505305bc8638edbb1977c9a9fd4e8100f5c8b0

validation.csv (3.5 MB )
SHA1: ad89b7763b2cc4c72ab90f5c253b1d6ed83b5cd1

public.csv (12 MB )
SHA1: 8ed2431d0af36bfcc1de51bca4b50af59d1ae16f

ESA_xView3_sceneName_mapping.csv (71 KB )
SHA1: 09357dfd8c4c1a0f45f7d0c6999510f63eec848d

SARFish labels

GRD_train.csv (17 MB)
SHA1: 64a3a294a1c9914e92f832d82fe01e68824c70ce

SLC_train.csv (17 MB)
SHA1: db646d71dbaa217f969440d1878a220d43e54505

GRD_validation.csv (6 MB)
SHA1: a3718b4c092170773fd6a021d9dfa4f194a24616

SLC_validation.csv (6 MB)
SHA1: bcbe43f9be9dd6d432453fcff0021bb5a0248da9

Shoreline data
Shoreline files are of moderate size, and also available for direct download. When your download has finished, verify the file integrity using the SHA1 hashes given for the respective file:

shoreline/train.tar.gz (554 MB archive; 1 GB decompressed)
SHA1: 09b217bde47079a50b713a0ff72b5b69ab2c5235

shoreline/validation.tar.gz (80 MB archive; 152 MB decompressed)
SHA1: 0256d98a42583ffa3785bc6c997d3910b2ea46a0

shoreline/public.tar.gz (259 MB archive; 491 MB decompressed)
SHA1: 67e6389d71a0c0148c05ae836b738f2bfb465986

Verifying file integrity
SHA1 hashes are provided to verify the integrity of your downloaded files. Compute the SHA1 values of each downloaded file using a command like shasum -a 1 FILENAME, then compare the result computed from your local file to the SHA1 strings given here for that file. If the values match, then your file is good. If your result does not match the value given here, something has gone wrong with your download and you should re-download, perhaps using a more reliable connection.

Interrupted Downloads and Stale Links
To maximize your download speed, your downloads are customized to stream data from a nearby server. If your download is interrupted, or if a significant time has elapsed since you loaded this page, you may need to refresh the page in your browser to obtain fresh download links.

Imagery
Four datasets are provided for download. The tiny set is a subsample of five training scenes and two validation scenes that allows solvers to work through the reference implementation and get a sense of the data and task without downloading the entire xView3 dataset. The validation set is for solvers to validate detections locally, and includes high-quality labels for 50 scenes. The training set contains over 500 scenes. We recommend having at least 2TB of disk space available to download and decompress the training set. The solvers will produce and submit their predictions on the public leaderboard set, which contains 150 scenes.
