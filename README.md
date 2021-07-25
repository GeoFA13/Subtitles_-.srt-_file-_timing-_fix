# Subtitles_srt-file-timing_fix
Empirically synchronize delayed/advanced subtitles for .srt files for your movie files. Increase/decrease unit in this initial version is fixed at 1 second. Will enable milliseconds adjust, as well as upload .exe file for non-LabVIEW users.

How to use:
1. srt file is loaded through file path input "SRT file in".
2. Timing increase/decrease is set with numeric control "Ajuste de tiempo".
3. Run once and a new srt file named "adj_(nput file name)" will be created in input file location.
4. Test new srt file and adjust again if necessary.

* Remember to reload fixed srt file at video on every test.

To do:
- Add millisecond adjust.
- Improve code. (Eventhough it takes no more than a couple seconds, it is obviously not the best way to get the job done. Will work on that too.)
- Upload executable file, so that non-LabVIEW users can use this tiny tool. :)
* This first version only takes into account changing inital and final dialogs timepoints as reference. I still have not figured out how to deal with overall dialog duration or adding additional mid-points as reference.
