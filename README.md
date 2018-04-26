%-------------------------
% Resume in Latex
% Author : Kush Shah
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[pdftex]{hyperref}
\usepackage{fancyhdr}
\usepackage[a4paper,bindingoffset=0.2in,%
            left=.5in,right=1in,top=1in,bottom=1in,%
            footskip=.25in]{geometry}

\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.375in}
\addtolength{\evensidemargin}{-0.375in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

%-------------------------
% Custom commands
\newcommand{\resumeItem}[2]{
  \item\small{
    \textbf{#1}{: #2 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-1pt}\item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-5pt}
}

\newcommand{\resumeSubItem}[2]{\resumeItem{#1}{#2}\vspace{-4pt}}

\renewcommand{\labelitemii}{$\circ$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}
\usepackage{hyperref}
\hypersetup{
    colorlinks=true,
    urlcolor=blue,
}
%-------------------------------------------
%%%%%%  CV STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING-----------------
\begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
  \textbf{\Large Kush Shah} & Email : \href{mailto:ks4437@nyu.edu}{ks4437@nyu.edu}\\
  \href{http://kushrshah.com/}{http://www.kushrshah.com} & Mobile : +1-404-769-6661 \\
  \href{https://www.linkedin.com/in/kush289shah/}{https://www.linkedin.com/in/kush289shah/} & \href{https://github.com/kushshah289}{https://github.com/kushshah289}
  
\end{tabular*}


%-----------EDUCATION-----------------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {New York University}{New York, NY}
      {Master of Science in Computer Engineering}{Sep. 2016 -- May. 2018}
    \resumeSubheading
      {Charotar University of Science and Technology}{Gujarat, India}
      {Bachelor of Engineering in Computer Science}{Aug. 2012 -- May. 2016}
  \resumeSubHeadingListEnd

%--------PROGRAMMING SKILLS------------
\section{Programming Skills}
  \resumeSubHeadingListStart
    {
      \textbf{Programming Languages}{: C++, JAVA, Python.}
      \newline
      \textbf{Web Development}{: JavaScript ES6, SQL, NoSQL, MEAN Stack, PHP, NodeJS, ReactJS, HTML5, CSS3.}
      \newline
      \textbf{Tools}{: AWS, Heroku, Git, Semaphoreci, Vagrant, Docker.}
      \newline
      \textbf{OS}{: LINUX, MacOS, Windows}
      \newline
      \textbf{Languages}{: English, Hindi, German(A1), Gujarati}
    }
  \resumeSubHeadingListEnd

%-----------EXPERIENCE-----------------
\section{Experience}
  \resumeSubHeadingListStart

    \resumeSubheading
      {NYU Center of Urban Science + Progress}{New York, NY}
      {Teaching Assistant}{Feb 2018 - Present}
      \resumeItemListStart
        \item
          {Assisted in coursework and assignments for Data Visualization course. Helped students with their queries about D3.js.}
        \item
          {Taught JavaScript ES6, React Framework and database concepts.}
      \resumeItemListEnd

    \resumeSubheading
      {Codegurad Inc}{Atlanta, GA}
      {Software Engineer}{May 2017 - Aug 2017}
      \resumeItemListStart
        \item
          {Responsible to develop an Uptime Monitor for the Codeguard application’s dashboard.}
        \item
          {Created a program with NodeJS to asynchronously check the website status using Google Chrome Headless. We were able to scale the application to process large number of websites by increasing workers.}
        \item
          {Created RESTful APIs to send data to the main Codeguard application. Used Redis and resque libraries to queue jobs and schedule tasks for the workers. Created test cases using TDD with Rspec and minitest.}
      \resumeItemListEnd

    \resumeSubheading
      {NYU College of Art and Science, IT Department}{New York, NY}
      {Web Developer}{Feb 2017 and May 2017}
      \resumeItemListStart
        \item
          {Redesigned the NYU CAS’s cohort website to improve the UI and make the registration process intuitive for the new NYU students. Used AJAX and Javascript along with jQuery.}
      \resumeItemListEnd

    \resumeSubheading
      {Saggi Soft Solutions}{Ahmedabad, India}
      {Software Engineer}{Jan 2016 - May 2016}
      \resumeItemListStart
        \item
          {Developed backend and database of Petts.Club along with the admin panel for the website. The data retrieval was done using Asynchronous JavaScript calls, which enabled the website to fetch data faster and with reduced server calls along with the cost of servers as the project was deployed on cloud.}
        \item
          {Developed the sub-routines, triggers and stored-procedures for this website which enhanced the maintainability and security of the website.}
        \item
        {Contributed in developing a responsive front-end of the system using HTML5, CSS3 and JavaScript.}
      \resumeItemListEnd

  \resumeSubHeadingListEnd

%-----------PROJECTS-----------------
\section{Projects}
  \resumeSubHeadingListStart
    \resumeSubItem{Weather forecast App }
      {Used dark sky API, NodeJS, ExpressJS and MongoDB database with RESTful HTTP interface. It provides 100\% uptime by using different primary and secondary services like Google’s geocoding services. }
    \resumeSubItem{MIPS processor Simulator}
      {Implemented an instruction-level simulator, cache simulator and a branch predictor of MIPS processor in C++.}
    \resumeSubItem{Neural Style Transfer, Machine Learning }
      {Created a machine learning project on neural style transfer that mixes images with different types of styles or textures. Used Neural Networks to amplify features and patterns in input image.}
    \resumeSubItem{Vehicle Tracking System }
      {Created a Vehicle Tracking System which updates location on a web-portal in real-time using Google Map API and Atmel AVR microcontroller. Used open-source technologies to build the system which helped reduce the cost. The performance of final product was at par with the commercial products available. The system was designed with embedded C/C++. }
  \resumeSubHeadingListEnd

%



%-------------------------------------------
\end{document}
