# 2col-resume-template
 
Template created in LaTeX for a two column resume. Has a 65-30 (5 for margins) split using minipages. All new commands to create sections have been commented and included in the preamble, the right hand section still needs a bit of formatting but most of it is easily usable through tables and including vertical spaces.

## Issues:
There is overflow of text on the right hand column if you keep typing, so you will have to manually enter \\ in order for the text to wrap into the next line, there may be need of trial and error.

The indentation upon opening of the file itself for some reason (at least in vim) is really bad. A quick solution is to open the template and type:

```
:%s/^\s\+//
```
This will get rid of all the white space, then type:

```
gg=G
```

Which will take you to the top of the file, and add indentation where is needed.

## Example:

This is what it rougly looks like, with the macros (in the preamble) it's fairly easy to play around with the absolute spacing and orientation of the section, the <++> signs indicate that the field needs to have content entered in it.

![alt text](https://github.com/Yatin-Kapur/2col-resume-template/blob/master/sample.png "Resume Example")
