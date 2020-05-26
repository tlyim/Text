# Text

* currently contain code to extract MC answers from potentially problematic answer sheets contained in multiple-page pdf files (eg, answer sheet spreading across pages or contaminated by spillover from the preceding page)
  - handle several types of problematic cases illustrated in a sample file in this repo
  - also write back on page 1 of an exam script pdf file the marks for the MC and long questions by 
    - converting the page to an image object
    - output the image object as an image file with texts added to it
    - combine the modified page 1 with the remaining pages of the pdf file to give the final output file
