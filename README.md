# Workflow

1. **Clone** this currOpinRvw GitHub repository to your local machine. You will want the GitHub application installed. I suggest keeping the your local repository of this project in a personal Dropbox folder, so that your copy is sync'd between your devices and you can work anywhere. 
2. Then just **write** and make changes! Lets work with `currOpin_main.txt` as our main manuscript document for now. We can do page layout and formatting in Word later.
3. Then when you are at your primary computer with the GitHub application installed, press the **'Commit'** button in GitHub and add a brief commit message on your changes.
4. **Sync** the changes back to the remote shared repository. 
	* Everything is versioned using this git based workflow and we can seamlessly merge changes, revert changes, and make selective merges by looking at the diff. 


# Info
*  The `currOpin_main.txt` file is just a plain text file you can work in **any** text editing application. 
    * Mac OSX: TextEdit, [WriteRoom](http://www.hogbaysoftware.com/products/writeroom), iA Writer, or Byword is recommended. 
    * iOS: WriteRoom, Byword, [Notesy](http://notesy-app.com), iA Writer, or Nebulous Notes is recommended. 
    * Windows: Notepad++ is recommended.
    * If preference is to write in Microsoft Word, just make sure to save as **plain** text file. Though modern software should no longer have any issues with Unicode text encoding (most web documents have been Unicode UTF-8 for many years now) be careful about text encoding issues on Mac versions of Microsoft Word when opening/saving plain text UTF-8 encoded documents. [Surprisingly, Word still manages to garble stuff up](http://answers.microsoft.com/en-us/mac/forum/macoffice2011-macword/why-does-word-for-mac-always-mangle-unicode-text/ad95c7ab-ab56-45af-8a74-51d26f079d25).

* This main.txt file uses ['Markdown' style formatting](http://daringfireball.net/projects/markdown/syntax) which is completely optional (that is how the document and outline and even this README is currently formatted. GitHub is very markdown friendly).

* Since `currOpin_outline.md` file is also in markdown format, it was rendered as html and pdf and saved using the [Marked](http://markedapp.com) markdown preview application. 

* The .md extension is just an alternative to the .txt extension for plain text files to help applications know when a file should be rendered using markdown formatting.

[View the review outline](currOpin_outline.md)

[View the review outline pdf](currOpin_outline.pdf)


# Markdown to Word

[Instructions for how to convert multimarkdown manuscript](https://gist.github.com/ackman678/6391902) with cite-keys for bibliography management into a Word document if needed


## Primate fetal development

Vanhatalo Eur J Neurosci 2005. Preterm human infant occipital cortex EEG recordings at 32 - 46 weeks conception age; 30 - 44 weeks pregnancy/gestation age

Chalupa in vitro macaque retinal wave recording works done at E51 - E76.  Retinal waves first occurred at E60 (>100 d. before birth).

Pasko unilateral enucleation experiments at E60-90 in macaque. Dramatically altered LGN layers and ODCs in cortex abolished (1981, 1988 Science review).
H. Kennedy bilateral enucleation experiments at same age, nissl is fine in visual cortex but Area 17 surface area dramatically shrunken, less 'radial units'.

Macaque monkey neocortical neurogenesis

age  | layer       
---- | ----------  
E40  | subplate, L6
E56  | L5          
E100 | L2/3        

Macaque monkeys are born at E165 (full term), maybe as early as E140. 

## Calculate when human retinal waves likely to occur

E60 monkey retinal waves / E165 monkey full term == **x** human retinal waves / E266  human full term
**x = E96 => 14 weeks.  Beginning of second trimester**

So human retinal waves likely occur from at least the beginning of the second trimester (overlapping with thalamocortical targeting and upper layer cortical neurogenesis). In relation to when mouse and ferret retinal waves occur, it would appear that the human retinal waves would continue to into the early to mid third trimester (when the retina is able to detect light). *But since patterned vision has not begun till human birth, is it possible that retinal waves or some other intrinsic activity pattern serves to provide visual circuit activation until birth?*  In any case, the likely timing of retinal waves in primates sets these spontaneous activity patterns up for having a disproportionate influence on higher order connectivity within and between different sub-cortical and cortical areas. 


## Ferret, cat, rabbit, and rodent development

Species | Day of birth | Day of eye opening | Onset of vision ( days of development) | Reference literature                                                                                 
------- | ------------ | ------------------ | -------------------------------------- | ---------------------------------------------------------------------------------------------------  
ferret  | E42          | P30 - P34          | 42+32=74                               | Durack & Katz Cerebral Cortex  1996: 'as ferrets do not open their eyes until approximately P31'     
cat     | E64          | P7 - P11           | 64+9=73                                | C. Blakemore J Physiol 1974: 'usually about 8-10 days'                                               
rabbit  | E31          | P11                | 31+11=42                               | Syed & Zhou J Physiol 2004: 'waves would disappear shortly after P8, probably around eye opening (P11)'  
mouse   | E19-E21      | P11-P14            | 21+13=34                               | Laboratory Mouse Handbook. Ears open P5.                                                             
rat     | E21-E23      | P13-P14            | 23+13=36                               | Colonnese JNS 2010: '90% of the rats opened their eyes between P13 and P14'                          


