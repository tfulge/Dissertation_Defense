---
title: "The Political Economy of Higher Education: Preferences, Inequality, and Policy Change"
subtitle: "Dissertationskolloquium"
date: "13. Mai 2022"
author: Timm Fulge
bibliography: bib/mybib.bib
output:
  beamer_presentation:
    theme: BIGSSS
    fonttheme: professionalfonts
    slide_level: 2
header-includes:
  - \AtBeginEnvironment{CSLReferences}{\tiny} # small font size in references section
---



---
nocite: |
    @Thelen.2004,
    @Streeck.2005
    @Mahoney.2010b,
    @Gerring.2007
---


## Einstieg 

![Enrolment in Secondary and Higher Education, Developed Countries, 1950-2010](Figures/FiguresEnrolment_over_time_new-1.pdf) 
\pause

\begin{itemize}
\item{Genereller Trend zur Expansion}
\item{Hochschulbildung: Bemerkenswerte Varianz zwischen einzelnen Ländern (nicht nur in Bezug auf Enrolment)}
\end{itemize}

## Einstieg 

Higher Education is special!

\pause

\begin{alertblock}{Leitfragen}
\begin{itemize}[<+->]
\item{Wie können Hochschulsysteme möglichst ganzheitlich konzeptualisiert werden?}
\item{Welche Varianz zeigt sich zwischen Ländern sowie über die Zeit?}
\item{Welche (re)distributiven Implikationen haben unterschiedliche Designs von Hochschulsystemen?}
\item{Wie können Unterschiede erklärt werden?}
\begin{itemize}
\item{Sozio-ökonomischer Problemdruck}
\item{Pfadabhängigkeiten}
\item{Parteipolitik}
\end{itemize}
\end{itemize}
\end{alertblock}

## Einstieg

**Kumulative Dissertation**, auf Englisch verfasst und bestehend Introduction und drei Einzelarbeiten in alleiniger Autorenschaft:

\begin{itemize}
\item{\textit{The Trilemma of Higher Education and Equality of Opportunity: Social Background, Access to Higher Education and the Moderating Impact of Enrolment and Public Subsidization}}
\item{\textit{Explaining Institutional Change in UK Higher Education: Towards A Partisan Theory?}}
\item{\textit{The Role of Parties in the Distributive Politics of Higher Education}}
\end{itemize}

## Stand der Forschung

![Evolution der Literatur zum Forschungsgegenstand](Figures/Intro/EvolutionOfTheField.drawio.pdf) 

## Konzeptioneller Rahmen

![Modell der politischen Ökonomie der Hochschulbildung](Figures/Intro/polecon_final.drawio.pdf) 

## Paper #1: *The Trilemma of Higher Education and Equality of Opportunity* (Forschungsdesign)


\begin{block}{Forschungsfrage}
\scriptsize
Wie strukturiert das institutionelle Design des Hochschulsystems den Zugang zu universitärer Bildung? Mindert oder verstärkt es Effekte sozialer Herkunft?
\end{block}

\pause

\begin{exampleblock}{Theorie}
\begin{itemize}
\scriptsize
\item{Ungleichheitsbezogene Bildungsforschung: Soziale Herkunft (hier = elterlicher Bildungsstand) sagt systematisch Erfolg im Bildungssystem voraus}
\begin{itemize}
\scriptsize
\item{Kosten-Nutzen-Kalkulation: $P_{HE} = (p * U) - C_{HE}$}
\end{itemize}
\item{Politische Ökonomie der Hochschulbildung: Studierendenzahl (\textit{Enrolment}) und Level öffentlicher Bezuschussung (\textit{Public Subsidization}) könnte Kosten-Nutzen-Kalkulation beeinflussen}
\end{itemize}
\end{exampleblock}

\pause 

\begin{alertblock}{Daten \& Methode}
\begin{itemize}
\scriptsize
\item{Zentrale Variablen: \textit{Student} (AV); \textit{Parental Education}, \textit{Enrolment}, \textit{Public Subsidization} (UVs)}
\item{Daten: Gepoolte Wellen des European Social Survey (2002-2010), Makrodaten vom UNESCO Institute for Statistics (22 Länder, 16.278 Beobachtungen)}
\item{Methode: Hierarchische logistische Regression mit Random Intercepts + Slopes}
\end{itemize}
\end{alertblock}

## Paper #1: *The Trilemma of Higher Education and Equality of Opportunity* (Ergebnisse)
**H1:** Je niedriger das elterliche Bildungsniveau, desto geringer die 
Wahrscheinlichkeit, ein Studium aufzunehmen
\scriptsize 
$logit\{Pr(Student_{ij} = 1|,x_{ij}|,\zeta_{j})\} = \beta_{1} + \beta_{2}Parental\:Education_{ij} + \cdots + \zeta_{j} + \epsilon_{ij}$
\begin{figure}
\includegraphics[width=55.56in,height=5cm]{Figures/01_Inequality/Figure 4} \caption{Geschätzte Randmittel, Fixed Effect von elterlicher Bildung auf Studiumswahrscheinlichkeit}\label{fig:unnamed-chunk-4}
\end{figure}

## Paper #1: *The Trilemma of Higher Education and Equality of Opportunity* (Ergebnisse)
**H2:** Die Effektstärke der elterlichen Bildung auf die Studiumswahrscheinlichkeit variiert zwischen den Ländern
\scriptsize 
$logit\{Pr(Student_{ij} = 1|,x_{ij}|,\zeta_{j})\} = \beta_{1} + \beta_{2}x_{2ij} + \cdots + \zeta_{j}Parental\:Education_{ij} + \epsilon_{ij}$
\begin{figure}
\includegraphics[width=55.56in,height=5cm]{Figures/01_Inequality/Figure 3} \caption{Effekt elterlicher Bildung auf Studiumswahrscheinlichkeit, nach Ländern}\label{fig:unnamed-chunk-5}
\end{figure}

## Paper #1: *The Trilemma of Higher Education and Equality of Opportunity* (Ergebnisse)
**H3:** Die Effektstärke der elterlichen Bildung auf die Studiumswahrscheinlichkeit wird (auch) vom institutionellen Design des Hochschulsystems (*Enrolment*, *Public Subsidization*) beeinflusst
\scriptsize 
$logit\{Pr(Student_{ij} = 1|,x_{ij}|,\zeta_{j})\} = \beta_{1} + \beta_{2}Parental\:Education_{ij} *\beta_{3}Enrolment\: /\: Public\:Subsidization_{j} + \cdots + \zeta_{j} + \epsilon_{i}$
\begin{figure}
\includegraphics[width=14.25in,height=5cm]{Figures/01_Inequality/RegTablet} \end{figure}

## Paper #1: *The Trilemma of Higher Education and Equality of Opportunity* (Ergebnisse)
**H3:** Die Effektstärke der elterlichen Bildung auf die Studiumswahrscheinlichkeit wird (auch) vom institutionellen Design des Hochschulsystems (*Enrolment*, *Public Subsidization*) beeinflusst
\scriptsize 
$logit\{Pr(Student_{ij} = 1|,x_{ij}|,\zeta_{j})\} = \beta_{1} + \beta_{2}Parental\:Education_{ij} *\beta_{3}Enrolment\: /\: Public\:Subsidization_{j} + \cdots + \zeta_{j} + \epsilon_{i}$
\begin{figure}
\includegraphics[width=55.56in,height=5cm]{Figures/01_Inequality/Figure5} \caption{Cross-Level Interaktionseffekt von elterlicher Bildung und öffentlicher Bezuschussung auf Studiumswahrscheinlichkeit}\label{fig:unnamed-chunk-7}
\end{figure}

## Paper #1: *The Trilemma of Higher Education and Equality of Opportunity* (Zusammenfassung)

- Länderübergreifend starker Einfluss von sozialem Hintergrund auf Studiumswahrscheinlichkeit
\pause
- Effektstärke variiert erheblich zwischen den Ländern
\pause
- Teil der Varianz zwischen den Ländern kann mit dem Level öffentlicher Bezuschussung erklärt werden: Je generöser studentischer Subventionen sind, desto geringer fällt der Einfluss des sozialen Hintergrunds auf die Studiumswahrscheinlichkeit aus. Kein Effekt der Studierendenquote.
\pause
- Empirische Implikation: Trend zur Expansion des Hochschulsystems auf Kosten der Generösität der Subventionen könnte sich negativ auf sozialen Gradient auswirken
\begin{figure}
\includegraphics[width=55.56in,height=5cm]{Figures/01_Inequality/Figure2} \caption{Entwicklung der Hochschulsysteme, Veränderung 2002-2010}\label{fig:unnamed-chunk-8}
\end{figure}


## Paper #2: *Explaining Institutional Change in UK Higher Education: Towards A Partisan Theory?* (Forschungsdesign)


\begin{block}{Forschungsfragen}
\scriptsize
\begin{itemize}
\item{Wie kann das institutionelle Design von Hochschulsystemen beschrieben und über die Zeit nachgezeichnet werden?}
\item{Mit welchen Hemmnissen und Zielkonflikten ist die Politik bei Reformbemühungen konfrontiert?}
\item{Können generalisierbare parteipolitische Präferenzen zum Design von Hochschulsystemen identifiziert werden?}
\end{itemize}
\end{block}

\pause

\begin{exampleblock}{Theorie}
\begin{itemize}
\scriptsize
\item{Theoriebildender Ansatz}
\item{Analytischer Rahmen: Historischer Institutionalismus nach Kathleen Thelen (Thelen 2004, Streeck \& Thelen 2005, Mahoney \& Thelen 2010)}
\end{itemize}
\end{exampleblock}

\pause 

\begin{alertblock}{Daten \& Methode}
\begin{itemize}
\scriptsize
\item{Daten: Primär- und Sekundärliteratur}
\item{Methode: Dichte Beschreibung / Process Tracing}
\item{Fallauswahl: Diverse case-selection strategy nach Gerring (2007), vier Reformperioden zwischen 1963-2015}
\end{itemize}
\end{alertblock}



## Paper #2: *Explaining Institutional Change in UK Higher Education: Towards A Partisan Theory?* (Ergebnisse)

**Vier Perioden von Reformaktivität**
  
  \begin{itemize}
\item{Nachkriegskonsens (1963-1979)}
\begin{itemize}
\item{Moderate, gut finanzierte Expansion des Hochschulsektors}
\item{Großzügige Subventionen für Studierende, aber ausgeprägte soziale Ungleichheiten beim Hochschulzugang}
\item{Hohes Maß an Qualität / Pro-Kopf-Finanzierung}
\end{itemize}
\item{Kürzungspolitik unter Tory-Regierungen (1979-1997)}
\item{Wandel unter Labour (1997-2010)}
\item{Tory-LibDem Koalition, 2010-2015}
\end{itemize}

## Paper #2: *Explaining Institutional Change in UK Higher Education: Towards A Partisan Theory?* (Ergebnisse)

**Vier Perioden von Reformaktivität**
  
\begin{itemize}
\item{Nachkriegskonsens (1963-1979)}
\item{Kürzungspolitik unter Tory-Regierungen (1979-1997)}
\begin{itemize}
\item{Massive Kürzungen der öffentlichen Mittel für Universitäten}
\item{Zunächst Stagnation der Studierendenquote, später massive Expansion}
\item{$\rightarrow$ Halbierung der Pro-Kopf-Finanzierung}
\item{Reduzierung der Generösität von Stipendien für Studierende, Einführung von Studienkrediten}
\item{Element der Stratifikation innterhalb des Hochschulsektors, Schutz der Eliteinstitutionen}
\end{itemize}
\item{Wandel unter Labour (1997-2010)}
\item{Tory-LibDem Koalition, 2010-2015}
\end{itemize}

## Paper #2: *Explaining Institutional Change in UK Higher Education: Towards A Partisan Theory?* (Ergebnisse)

**Vier Perioden von Reformaktivität**
  
\begin{itemize}
\item{Nachkriegskonsens (1963-1979)}
\item{{Kürzungspolitik unter Tory-Regierungen (1979-1997)}
\item{Wandel unter Labour (1997-2010)}
\begin{itemize}
\item{Einführung von Studiengebühren 1997, Erhöhung 2004}
\item{Moderate Expansion der Studierendenquote}
\item{Studiengebühren und leichte Erhöhung öffentlicher Mittel für Universitäten. Qualität bleibt stabil}
\item{Einführung einkommensabhängiger Rückzahlung von Studienkrediten}
\end{itemize}
\item{Tory-LibDem Koalition, 2010-2015}
\end{itemize}

  ## Paper #2: *Explaining Institutional Change in UK Higher Education: Towards A Partisan Theory?* (Ergebnisse)
  
  **Vier Perioden von Reformaktivität**
    
\begin{itemize}
\item{Nachkriegskonsens (1963-1979)}
\item{{Kürzungspolitik unter Tory-Regierungen (1979-1997)}
\item{Wandel unter Labour (1997-2010)}
\item{Tory-LibDem Koalition, 2010-2015}
\begin{itemize}
\item{Studiengebühren verdreifacht}
\end{itemize}
\end{itemize}

## Beiträge der Dissertation zur Forschung

- Ungleichheit im Zugang zu Hochschulbildung im Zentrum der Analyse
  - Längs- und querschnittliche Effekte empirisch modelliert
  - 

- 


## dfjkdjflkdj 

\begin{columns}
\column{0.66\textwidth}
\begin{figure}
\includegraphics[height=6cm]{Figures/Intro/Enrolment_over_time-1} \caption{Geschätzte Randmittel, Fixed Effect von elterlicher Bildung auf Studiumswahrscheinlichkeit}\label{fig:unnamed-chunk-9}
\end{figure}
\column{0.33\textwidth}

Hier wird Text eingebracht \newline
\begin{itemize}[<+->]
\item{test 1 2 3}
\item{test 3 4 5}
\begin{itemize}
\item{mano a mano}
\end{itemize}
\end{itemize}

> - Eat eggs
> - Drink coffee
>    - Have at it

\end{columns}

## Einstieg 

Ist es möglich, einen Umlaut zu zeigen?

This article was written by @Ansell.2008b.

The same author has supporting evidence [@Ansell.2013].

Another argument was advanced by Garritzmann [-@garritzmann2016]

Does Markdown automatically expand on the references section [@Pierson.1993; @Hall.1996; @Hall.2001]?

## Slide with (incremental) Bullets

> - Eat eggs
> - Drink coffee
>    - Have at it

## Slide with R Output


```r
summary(cars)
```

```
##      speed           dist       
##  Min.   : 4.0   Min.   :  2.00  
##  1st Qu.:12.0   1st Qu.: 26.00  
##  Median :15.0   Median : 36.00  
##  Mean   :15.4   Mean   : 42.98  
##  3rd Qu.:19.0   3rd Qu.: 56.00  
##  Max.   :25.0   Max.   :120.00
```

## Slide with Plot

\begin{figure}
\includegraphics[height=4cm]{Figures/Intro/Enrolment_over_time-1} \caption{Illustration of higher education system ideal types}\label{fig:unnamed-chunk-10}
\end{figure}

- What happens if I put stuff here?

- Doesn't seem to automatically resize the plot

## Next slide with plot

![](Presentation_files/figure-beamer/unnamed-chunk-11-1.pdf)<!-- --> 
- Is he willing to do what I want here?

- By which I mean automatically resizing the image at hand

- He doesnt, not even now?


## Two column layout

\footnotesize
:::::::::::::: {.columns}
::: {.column}
\begin{figure}
\includegraphics[height=4cm]{Figures/Intro/Enrolment_over_time-1} \caption{Illustration of higher education system ideal types}\label{fig:unnamed-chunk-12}
\end{figure}
:::
::: {.column}
> - Eat eggs
> - Drink coffee
>    - Have at it
:::
::::::::::::::

## Final Test

Blocks

\begin{alertblock}{Theses}
1. The world is round \newline
2. It goes around
\end{alertblock}

## Referenzen {.allowframebreaks}
