[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/zlrrqfrw)
# CECS 378 Reading Assignment: Introduction to Computer Security

### Assignment Description
Answer the following questions from the chapter 1 reading from your textbook. You may work on these questions with one or two other partners, but *all* students must submit the document individually in their own repositories along with each student's name documented with the submission.

1. Define the term *computer security*.

"Computer security" secure information and safe from hackers and access and damage that ensures that data is private and accurate when needed 


2. What is the difference between passive and active security threats?

The difference between passive and active security threats is that the attacker just observes the data with out changing anything they may spy and gather information. In the other hand the active threats changes or damage data to get into the system and hackiung into the account and alternaring information 

3. Explain the difference between an attack surface and an attack tree.

The difference between an attack surface and an attaci tree could be that the surface is all the points on the system all the unsecure websites and sites the could use to get in, The attack trr is avidyal diagram that shows all the different way an attacker could acchive a goal like a map showing in different ways to break intob the system 

4. Consider an automated teller machine (ATM) in which users provide a personal identification number (PIN) and a card for account access. Give examples of confidentiality, integrity, and availability requirements associated with the system and, in each case, indicate the degree of importance of the requirement.

- Confidentiality: Keeping the pin and card information secret. The degree importance is high
- Integrity: make sure the transaction is correct and not tampered with importance of the degree is high
- Availiability: makung sure the ATM is working when users need it. The degree importance is moderate
  
5. Repeat question #4 for a telephone switching system that routes calls through a switching network based on the telephone number requested by the caller.

-Confidentiality: Protect the caller number and details 
-integity: Ensure the call is connected to the correct number 
- Availability: make sure the system is always working to route calls . The degree is importance 

6. List and briefly define the fundamental security design principles.
 - Give users only the access they need nothing more, whe something goes wrong, the system shouklf remain secure, use multiple steps of checks for sensituve actions , keep securitu mechanism
   
7. Consider a desktop publishing system used to produce documents for various organizations.
    
    1. Give an example of a type of publication for which confidentiality of the stored data is the most important requirement.
    - Confidentiality: A confidential report about a company future plans
    2. Give an example of a type of publication in which data integrity is the most important requirement.
     - integrity: A legal contract where any changes could cause problems
    3. Give an example in which system availability is the most important requirement.
    - Availiability: A new wevsite that must stya online to publish saily updates
9. For each of the following assets, assign a low, moderate, or high impact level for the loss of confidentiality, availability, and integrity, respectively. Justify your answers.
    
    1. An organization managing public information on its Web server.
      - Confidentiality: which is low and is becuase it is a public info
      - Integrity: is high and its becuase is wrong information and could confuse peple
      - Availiabitliy: is  high becuase pople expect the site to be abailiability 
    3. A law enforcement organization managing extremely sensitive investigative information.
       - Confidentiality: is High becuase it could endanger people or investigations
        -Integrity:is High becuase the errors could compromise investigations
        -Availability: is Moderate becuase  important, but can wait in non-emergencies
    4. A financial organization managing routine administrative information (not privacy-related information).
-Confidentiality: Moderate becuae is basic privacy concerns
-Integrity: Moderate becuase some mistakes could cause confusion
-Availability: Low becuase not immediately critical
    5. An information system used for large acquisitions in a contracting organization contains both sensitive, pre-solicitation phase contract information and routine administrative information. Assess the impact for the two data sets separately and the information system as a whole.

   sensitive:
Confidentiality: High bacuase sensitive contract info
Integrity: High becuase important for correct decision-making
Availability: Moderate.

Routine data:
Confidentiality: Low not sensitive
Integrity: Moderate.
Availability: Low.

    6. A power plant contains a SCADA (supervisory control and data acquisition) system con- trolling the distribution of electric power for a large military installation. The SCADA system contains both real-time sensor data and routine administrative information. Assess the impact for the two data sets separately and the information system as a whole.

-real time data: 
Confidentiality: moderate 
Integrity: high 
Availability: high 
incorrect data could cause failure 

-Routine administrative data: 
Confidentiality: Low 
Integrity: Moderate 
Availiability Moderate 
11. Develop an attack tree for gaining access to the contents of a physical safe.




12. Consider the following general code for allowing access to a resource:
 
    ``` C
    DWORD dwRet = IsAccessAllowed(...);
    if (dwRet == ERROR_ACCESS_DENIED) { // Security check failed.
    // Inform user that access is denied. } else {
    // Security check OK.
    }
    ```
    1. Explain the security flaw in this program.

   The security flaw in this program is that it assums the access denied with it has other error that might happend so the system might accidently allow acces 
 DWORD dwRet = IsAccessAllowed(...);
    if (dwRet != ERROR_ACCESS_DENIED) { // Security check failed.
    // Inform user that access is denied. } else {
    // Security check OK.
    }
   

### Deliverables

Commit the answers to the questions in a readable file to your git repository by the due date and time indicated with your repository on GitHub Classroom. The only approved file submission format is Markdown. Other formats will only be accepted with explicit approval.

#### Please note:

* Your writeup file *must* be done in [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) format and must be included in the repository as a separate file. View the file [`README.md`](README.md?plain=1) for an example of Markdown.
* Any included images or screenshots should be done in `*.jpg`, `*.png`, or `*.gif` formats, and be included individually as files in your repository (i.e. no binary ‘document’ with the images pasted inside).
* Screenshots or images *may* be linked in your Markdown file writeup if you wish to do so.
