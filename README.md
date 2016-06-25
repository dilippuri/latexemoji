# Use emoji in LaTeX #
*******************************************************************			

##Installing##
	download latexemoji folder from git
	store emoji_pics folder and latesemoji style file where your .tex is stored
*******************************************************************			

##Usage##
	include package by
		\usepackage{latexemoji}
	to include emoji in document
		\latexemoji{--emojiname--}
			read cheatsheet
*******************************************************************			

##Example##
	\documentclass[10pt]{article}
	\usepackage{latexemoji}
	\usepackage{graphics}

	\title{This is an example tex file to include emoji in latex}
	\author{Dilip Puri}

	\begin{document}
	\maketitle
		Hi, I am going to include emoji in latex. So I \latexemoji{heart} \LaTeX.\\
		I just \latexemoji{stuck_out_tongue_wink_eye}.\\
		
		Good bye! \latexemoji{wave}
	\end{document}
##Output##
![Output image of above latex script](output.jpg?raw=true "output image")
:pray:
*******************************************************************			
