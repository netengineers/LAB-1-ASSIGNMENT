# LAB-1-ASSIGNMENT
THE UNIVERSITY OF DODOMA
College of Informatics and Virtual Education
TN 310: WIRELESS NETWORKING
PRACTICAL I:OMNET ++ LAB ASSIGNMENT
Group Name:
S/No
NAMES
REG. NO.
COURSE
1.
SAIDI,OMARI
T/UDOM/2013/04810
BSc TE
2.
MINJA,STEVEN D
T/UDOM/2013/04136
BSc CE
3.
LOSHIRARI,GIDEON
T/UDOM/2013/4797
BSc TE
4.
MASERO,STEPHANO
T/UDOM/2013/04780
BSc TE
5.
MASINSI,TUMAINI J
T/UDOM/2013/04765
BSc TE
6.
MUHSIN,RAMADHANI
T/UDOM/2013/04812
BSc TE
7.
SANDE,NGOWI
T/UDOM/2013/04758
BSc TE
8.
VICENT,MAHENGE
T/UDOM/2013/04820
BSc TE
9.
NGOWI,ALEXANDA S
T/UDOM/2013/04782
BSc TE
10.
JACKSON,SAPULA
T/UDOM/2013/4140
BSc CE
1. In which file do we define our network topology?
ANSWER;
In tictoc1.ned file
2. How many nodes and links does our network have?
ANSWER;
Our network have one link and two nodes (toc and tic)
3. What does initialize () function do?
ANSWER;
Initialize function helps to begin simulation
4. What does handleMessage() function do?
ANSWER;
It handle (manage) incoming messages.
5. What does send() simulation kernel call do in the used in the initialize()
function?
ANSWER: It sends message out from the node
6. What does the Define module () macro do? Can this macro be used in a
Header file (.h file) and why?
ANSWER; YES:
Header files (.h) are designed to provide the information that will be needed in multiple files. Things like class declarations, function prototypes, and enumerations typically go in header files. In a word, "definitions".
7. In handleMessage () function, can we use another send () function right
After the first send () to send out the same message?
ANSWER: NO! We can’t.
8. Following activities and questions are related to dynamic memory allocation ad de-allocation in C++:
(a) Locate the following two statements in the initialize() function
cMessage *msg = new cMessage("tictocMsg");
send(msg, "out");
and comment them out. Rebuild the simulation model and run again.
What does happen?
ANSWER; nothing happen.
(b) Now, put these lines back in. But insert delete msg; between the
cMessage ... and send ... statements. Does the code compile without
errors? If yes, run it. Does it run without any errors? If no, what is
the error reported?
ANSWER;It has an error which is plugin path i.e. ./plugins
(c) Modify the line containing delete ... as follows delete msg; msg =
NULL, rebuild and run the code. What does happen?
ANSWER; Simulating tictock has encounter a problem,Run#0.
