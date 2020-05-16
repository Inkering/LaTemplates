---
title: Author's Notes 4//17/20
author: First Last
header-includes: |
    \usepackage{helvet}
	\usepackage[format=plain,
            font=it]{caption}
	\hypersetup{colorlinks=false,
            allbordercolors={0 0 0},
            pdfborderstyle={/S/U/W 1}}
	\renewcommand{\familydefault}{\sfdefault}
	\usepackage[a4paper,bindingoffset=0.2in,%
            left=1in,right=1in,top=1in,bottom=1in,%
            footskip=.25in]{geometry}
	\usepackage{float}
	\let\origfigure\figure
	\let\endorigfigure\endfigure
	\renewenvironment{figure}[1][2] {
		\expandafter\origfigure\expandafter[H]
	} {
		\endorigfigure
	}
---
# The Newsletter

This is a newsletter!



