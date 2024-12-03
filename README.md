%-------------------------
% Resume in Latex
% Author: Jake Gutierrez
% Based off of: https://github.com/sb2nov/resume
% License: MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{fontawesome5}
\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\usepackage{soul}
\usepackage{setspace}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}


%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that the generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\classesList}[4]{
    \item\small{
        {#1 #2 #3 #4 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------
% \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
%   \textbf{\href{http://sourabhbajaj.com/}{\Large Sourabh Bajaj}} & Email : \href{mailto:sourabh@sourabhbajaj.com}{sourabh@sourabhbajaj.com}\\
%   \href{http://sourabhbajaj.com/}{http://www.sourabhbajaj.com} & Mobile : +1-123-456-7890 \\
% \end{tabular*}

\begin{center}
    {\Huge \scshape Saurabh Pandey} \\ \vspace{1pt}
    % Gopalganj,Bihar \\ \vspace{1pt}
    \small \raisebox{-0.1\height}\faPhone\ 9234825220 ~ \href{mailto:saurabhpandey59254@gmail.com}{\raisebox{-0.2\height}\faEnvelope\  \underline{saurabhpandey59254@gmail.com}} ~ 
    \href{https://www.linkedin.com/in/saurabh-pandey-552712256}{\raisebox{-0.2\height}\faLinkedin\ \underline{Saurabh Pandey}}  ~
    \href{https://github.com/saurabhpandey2108}{\raisebox{-0.2\height}\faGithub\ \underline{Saurabh Pandey}}
    \vspace{-8pt} ~
    % \href{https://www.kaggle.com/saurabhpandey2108}{\raisebox{-0.2\height}\Kaggle\ \underline{Saurabh Kaggle}}
\end{center}

%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Birla Institute of Technology, Mesra}{Nov 2022 -- Present}
      {Bachelor of Technology (EEE)  CGPA - 8.20}{Ranchi, Jharkhand}
    \resumeSubheading
      {Central Public Academy }{2020 -- 2022}
      {12th-91.6\%}{Gorakhpur, UP}
  \resumeSubHeadingListEnd
%-----------PROGRAMMING SKILLS-----------
\section{Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \item{     \textbf{Languages}{: Python, SQL} \\
     \textbf{Technical Skills}{: Machine Learning, Data Analysis, Deep Learning, NLP, PCB Designing } \\
     
     \textbf{Tools}{: TensorFlow, scikit-learn, Keras, MySQL, Git, GitHub, Eagle} \\
     \textbf{Soft Skills}{: Leadership, Management, Teamwork, Communication, Public Speaking} \\
     
    }
 \end{itemize}
 \vspace{-16pt}

% %------RELEVANT COURSEWORK-------
% \section{Relevant Coursework}
%     %\resumeSubHeadingListStart
%         \begin{multicols}{1}
%             \begin{itemize}[itemsep=0pt, parsep=0pt]
%                 % \item\small Computer Networks
%                 % \item Natural Language Processing
%                 % \item Data Mining
%                 % \item Software Engineering
%                 \item Data Structure \& Algorithms
%                 \item Object Oriented Programming
%                 % \item Operating System
%             \end{itemize}
%         \end{multicols}
%         \vspace*{1.0\multicolsep}
%     %\resumeSubHeadingListEnd




%-----------PROJECTS-----------
\section{Projects}
    \vspace{-5pt}
    \resumeSubHeadingListStart

          \resumeProjectHeading
          {\textbf{Student Performance} $|$ \emph{Scikit-Learn, Random Forest}}
          {\href{https://github.com/saurabhpandey2108/Student-Performance}{GitHub Link}}
          \resumeItemListStart
            \resumeItem{The dataset includes 1,000 student records with features like gender, race, parental education, lunch type, test prep course, math scores, etc., to analyze academic performance. }

            \resumeItem{Demonstrated with Scikit-Learn to train and test the model over ensemble learning techniques such as Random Forest, KNN, and Decision trees with maximized accuracy up to 88.06.}
            
            % \resumeItem{ Implemented efficient state management and reusable components, optimizing app performance and scalability.}
            

             
            
          \resumeItemListEnd 
          \vspace{-5pt}
         
         \resumeProjectHeading
          {\textbf{Battery Voltage Prediction} $|$ \emph{ANN, LSTM}}
          {\href{https://github.com/saurabhpandey2108/Voltage-Prediction}{GitHub Link} 
          }
          \resumeItemListStart
            \resumeItem{Designed and developed a custom neural network from scratch, initially implementing an ANN before transitioning to LSTM for time-series predictions.}
            \resumeItem{Built a unique two-stage model: predicted 8 battery parameters, then computed voltage using mathematical equations and backpropagated error for optimization.}
            \resumeItem{Conducted hyperparameter tuning and manual optimization, achieving a 20 percent accuracy boost without relying on external libraries.}
          
          \resumeItemListEnd
          \vspace{-5pt}



          
          \resumeProjectHeading
          {\textbf{Holiday Package Prediciton} $|$ \emph{Scikit-Learn, Gradient Boost}}{\href{https://github.com/saurabhpandey2108/Holiday-Package-Prediction}{GitHub Link}
          }
          \resumeItemListStart
            \resumeItem{Developed a machine learning model to segment customers and optimize marketing strategies, efficiently targeting potential buyers for new Wellness Tourism packages.}
            \resumeItem{Implemented a data-driven approach to customer segmentation, creating tailored strategies that improved conversion rates, ultimately resulting in a 15 percent increase in average order value for Trips Travel.Com's promotional campaigns.}
          \resumeItemListEnd 
          \vspace{-5pt}
   
    \resumeSubHeadingListEnd
    \vspace{-5pt}




%

%-----------INVOLVEMENT---------------
\section{Achievements}
    \vspace{-5pt}
    \resumeSubHeadingListStart
            \resumeItemListStart
            
                \resumeItem{ Rank 1 in the Summer Mentorship Program organized by EEESOC BIT Mesra.}
                \resumeItem{ Secured second runner-up position in E-Baja SAEINDIA 2024 for separating HV and LV wirelessly.}
                \resumeItem{Awarded GP Birla Scholarship for excellent academic performance in MO-23 Semester.  }
            \resumeItemListEnd
        \vspace{-5pt}
    \resumeSubHeadingListEnd
\section{Leadership}
    \resumeSubHeadingListStart
        \resumeSubheading{General Secretary - Electrical and Electronics Engineering Society}{Jan 2023 -- Present}{}{}
        \vspace{-20pt}
            \resumeItemListStart
                \resumeItem{Successfully organized the 2 flagship events of the club, BOT-Soccer, both having a footfall of 1000+ students
and played a pivotal role in leading the project on Machine Learning}
                \resumeItem{Directed and executed the club’s recruitment initiative, engaging over 250+ students from the K23 Batch}
                
            \resumeItemListEnd

        \resumeSubheading{Electrical Lead - Team Aveon Racing}{Jan 2023 -- Present}{}{}
         \vspace{-20pt}
            \resumeItemListStart
            \resumeItem{Guided a team of 15 juniors in designing and developing the electrical system of an E-Baja SAEINDIA vehicle, contributing to a second runner-up finish at the final event. }
            \resumeItem{Developed a custom PCB to centralize low-voltage components and established a Wi-Fi connection between sender and receiver circuits for real-time monitoring and control.}
               
                
                
            \resumeItemListEnd
        \resumeSubheading{Executive Member - Society for Data Science}{Aug 2023 -- Present}{}{}
         \vspace{-20pt}
            \resumeItemListStart
            \resumeItem{Successfully organized the flagship events of the club, Data Science Summit, and played a pivotal role in organizing the workshop on Data Science. }
                
                
                
            \resumeItemListEnd
        
    \resumeSubHeadingListEnd
\end{document}
