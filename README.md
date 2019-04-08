# vobsub2srt_oem_patch
Patch VobSub2Srt Source Code to Allow OEM Engine Selection in Tesseract 4

This patch adds an option to vobsub2srt for Tesseract 4 OEM selection as I noticed tesseract 4 can have a lot of 
OCR problems when using the standard engine. Generally i do a --tesseract-oem 1 option to to OEM engine alone instead
of the combined or default model. I noticed this greatly reduces OCR mistakes on Linux machines. 

I use the traindata from the following page for tesseract 4 with OEM==1
https://github.com/tesseract-ocr/tesseract/wiki/Data-Files
