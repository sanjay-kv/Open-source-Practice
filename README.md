# Open-source-Practice

## open-source-practice Pull Requests
## Follow these steps carefully to ensure a smooth contribution process!

Repository for you to raise a Pull Request to **practice** open-source! 🎉

### Add your name to the alphabetical list and, optionally, a link to your GitHub account (in alphabetical order below your letter too)

### Option 1. Complete this process in GitHub (in your browser)

```mermaid
flowchart LR
    Fork[Fork the project]-->branch[Create a New Branch]
    branch-->Edit[Edit file]
    Edit-->commit[Commit the changes]
    commit -->|Finally|creatpr((Create a Pull Request))
```

**1. Fork the project:**

- Click the gray <kbd>Fork</kbd> button at the top right of the previous page. This creates your copy of the project and saves it as a new repository in your GitHub account.
  ![image](https://github.com/GSSoC24/being-an-GSSoc24/assets/166531702/a50b0ed1-84b6-4254-bd7c-d8dbb2839466)

**2. Create a New Branch:**

- On your new repository's page, click the gray main button in the upper left to reveal a dropdown menu.
- Enter the name of your new branch in the text box. (Branch names usually refer to what is being changed. Example: nameAdd).
  -Click on Create branch <new branch name>, which will automatically take you to your new branch. You can make edits on the main branch, but this may cause issues down the line. The best practice is to create a new branch for each separate issue you work on. That way your main branch remains in sync with Gssoc's main branch.

**3. Edit:**

- On the top right of the Readme file, click on the pencil icon to edit the file by **adding your name and your GitHub profile link to the section that matches your Initial in [this list](https://github.com/GSSoC24/being-an-GSSoc24/blob/main/docs/readme.md#GSSoC24-Community). Make sure that your name is in alphabetical order.**
- After editing the Readme file, add a commit message and click on the green button saying "Commit Changes". Make sure you have selected the branch you have created.

**4. Raise a Pull Request:**

- Click `Pull Requests` option in your forked repository (which is the third option at the top of this page after the options `Code` and `Issues`).
- Click the green New Pull Request button. This will prep the new pull request for you by auto-filling the base repository: base with 'GssocCommunity: main' AND auto-filling your head repository: compare with your repository: main 
- Click on your head repository's `compare` dropdown, and switch branches from your 'main' branch to `<new branch name>`.
- Finally, click the green `Create Pull Request` button. Great job! You did it!

You can ask questions by raising an [issue](https://github.com/GSSoC24/being-an-GSSoc24/issues).

### Option 2. Complete this process on your computer (locally)

**1. Fork the project:**

- Click the gray <kbd>Fork</kbd> button at the top right of the previous page. This creates your copy of the project and saves it as a new repository in your GitHub account.
  ![image](https://github.com/GSSoC24/being-an-GSSoc24/assets/166531702/8244b3df-7904-4f07-9447-7962cb504a34)

**2. Clone this project on your computer:**

- Go to your profile. You will find forked repo named **_open-source-practice_**. go to the repo by clicking on it.
- Click on the green Code button, then either the HTTPS or SSH option, and, click the icon to copy the URL. Now you have a copy of the project. Thus, you can play around with it locally on your computer.

- Run the following commands into a terminal window (Command Prompt, Powershell, Terminal, Bash, ZSH). Do this to download the forked copy of this repository to your computer.
  ![image](https://github.com/GSSoC24/being-an-GSSoc24/assets/166531702/9c41e4fe-438b-4747-8789-ff75e092fef9)

```bash
  git clone https://github.com/GSSoC24/being-an-GSSoc24.git
```

- Switch to the cloned folder. You can paste this command into the same terminal window. ![image](https://github.com/GSSoC24/being-an-GSSoc24/assets/166531702/590d6314-70b9-478d-939f-3c0e1dcf4ab4)

```bash
  cd being-an-GSSoc24
```

**3. Open in code Editor:**

- Open the `README.md` file
  ![image](https://github.com/GSSoC24/being-an-GSSoc24/assets/166531702/dd43df00-e1f2-42fa-8714-4a5731a1027f)

**4. Create a new branch:**
![image](https://github.com/GSSoC24/being-an-GSSoc24/assets/166531702/55059bd9-05f0-4f36-9205-9eb926831a19)

- Your username would make a good branch because it's unique.  
  ![image](https://github.com/GSSoC24/being-an-GSSoc24/assets/166531702/8eee07c1-120b-4022-8677-932b4dbe89d5)

```bash
  git checkout -b <name-of-new-branch>
```

**5. Edit the File:**
![image](https://github.com/GSSoC24/being-an-GSSoc24/assets/166531702/2d12a4e1-f18f-4e7d-b74e-590487016c70)

- **Add your name to the section that matches your Initial in [this list](https://github.com/EddieHubCommunity/open-source-practice#hacktoberfest-community), make sure that your name is in alphabetical order. Then save your changes.**

- For example
  `- [Full Name](https://github.com/your-username)`

**5. Stage your changes:**

```bash
  git add README.md
```

or

```bash
  git add .
```

**6. Commit the changes:**
![image](https://github.com/GSSoC24/being-an-GSSoc24/assets/166531702/e22f8f77-74e9-42a8-af0c-9caa23f5020b)

```bash
  git commit -m "Add <your-github-username>"
```

- Check the status of your repository.

```bash
  git status
```

- The response should be like this:
  ![image](https://github.com/GSSoC24/being-an-GSSoc24/assets/166531702/443ed4e6-6105-44e5-9ca2-d87d70a83986)

```bash
On branch <name-of-your-branch>
nothing to commit, working tree clean
```

**7. Pushing your repository to GitHub:**

```bash
  git push origin <name-of-your-branch>
```

or

```bash
  git branch -M main
  git push -u origin main
```

![image](https://github.com/GSSoC24/being-an-GSSoc24/assets/166531702/88211c3f-61dd-4851-b066-4791b988013c)

> **Warning**: If you get an error message like the one below, you probably forgot to fork the repository before cloning it. It is best to start over and fork the project repository first.

```bash
ERROR: Permission to https://github.com/GSSoC24/being-an-GSSoc24 denied to <your-github-username>.
fatal: Could not read from remote repository.
Please make sure you have the correct access rights and that the repository exists.
```

**8. Raise a Pull Request:**

- On the GitHub website, navigate to your forked repo - on the top of the files section, you'll notice a new section containing a `Compare & Pull Request` button! ![createpr]

- Click on that button, this will load a new page, comparing the local branch in your forked repository against the main branch in the GSSoC'24 Being an Gssoc repository. Do not make any changes in the selected values of the branches (do so only if needed), and click the green `Create Pull Request` button.
  Note: A pull request allows us to merge your changes with the original project repo.

- Your pull request will be reviewed and then eventually merged.

Hurray! You successfully made your first contribution! 🎉

---

## How can I fix a merge conflict?

A GitHub conflict is when people make changes to the same area or line in a file. This must be fixed before it is merged to prevent collision in the main branch.

- **To read more about this, go to [GitHub Docs - About Merge Conflicts](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/about-merge-conflicts)**

- **To find out about how to fix a Git Conflict, go to [GitHub Docs - Resolve Merge Conflict](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github)**

## `GSSoC24-Community`

### **Contents**

| [A](#a) | [B](#b) | [C](#c) | [D](#d) | [E](#e) | [F](#f) | [G](#g) | [H](#h) | [I](#i) | [J](#j) | [K](#k) | [L](#l) | [M](#m) | [N](#n) | [O](#o)
| [P](#p) | [Q](#q) | [R](#r) | [S](#s) | [T](#t) | [U](#u) | [V](#v) | [W](#w) | [X](#x) | [Y](#y) | [Z](#z) | [0-9](#0-9) |

- ### **A**


  - Abdul{https://github.com/abd0777}
  - [Anushree Nair](https://github.com/anushreenair)
  - [Aditi Tapariya](https://github.com/adititapariya)
  - [Ayushi Baijal](https://github.com/ABaijal9)
  - [Aabhirup Paul](https://github.com/paul-abhirup)
  - [Anshika Saini](https://github.com/Anshikaa-Saini)
 -  [Anushree mehta](https://github.com/anushreemehta6)
  -  [Akshayata Chandramouli](https://github.com/Akshayata101)
 -  [Anushka Chauke](https://github.com/23Anushkac)
  - [Aarya Balwadkar](https://github.com/AaryaBalwadkar)
  - [Agrima Singh](https://github.com/Agrima11)
  - [Aditya Jasoriya](https://github.com/Aditya01229)
  - [Amit Dhiman](https://github.com/amitdhiman5086)
  - [Ayush_Pant](https://github.com/ayushpant007)
  - [Ankita Waghode ](https://github.com/AnkitaWaghode25)
  - [Anshika Gupta](https://github.com/anshika-gupta21)
  - [Akhil Jain](https://github.com/AkhilJain5)
  - [Anushka Jain](https://github.com/AnushkaJainFirst)
  - [Amrita_sinha](https://github.com/asinha828)
  - [Aryan ](https://github.com/aryan)
  - [Arya Davare](https://github.com/aryadavare19)
  - [Aabhirup Paul](https://github.com/paul-abhirup)
 -  [Apurva Dharam](https://github.com/ApurvaDharam)
 -  [Ambika](https://github.com/Ambika03p)
  - [Arnab Mitra](https://github.com/arnab-mitra)
  -  [Aditya Singh](https://github.com/ascoder1109)
  - [Arjav Sankadasariya](https://github.com/arjav-sankadasariya)
  - [Amaan Sayyed](https://github.com/Viole07)
   - [Avineshwar](https://github.com/GAVINESHWAR)
  - [Avishkar Dhanorkar](https://github.com/avidhanorkar)
  - [Aakruti Kalia](https://github.com/akku-07)
  - [Anjali Vanguri](https://github.com/a-n-u-vanguri)
  - [Ananya Ravikiran Vastare](https://github.com/Ananya-vastare)
  - [Anshika Saini](https://github.com/Anshikaa-Saini) 
 -  [AYush](https://github.com/ayush-kumarrai)
 -  [Arya Hawaldar](https://github.com/aryah22)
- [Aabhirup Paul](https://github.com/paul-abhirup)
- [Aakruti Kalia](https://github.com/akku-07)
- [Abankita Behera](https://github.com/Abankita)
- [Abhishek Agarwal](https://github.com/AbhiBab)
- [Aditi Kapil](https://github.com/Aditi31kapil)
- [Aditi Singh](https://github.com/aditibais)
- [Aksh Maheshwari](https://github.com/AkshMaheshwari)
- [Amrutha](https://github.com/AmruthaPariprolu)
- [Anavi Gupta](https://github.com/Anavi972)
- [Ancelia Patrao](https://github.com/ancelia06)
- [Ankan Mukhopadhyay](https://github.com/Peart-Guy)
- [Ansh Bhatt](https://github.com/BhattAnsh)
- [Anshika Saini](https://github.com/Anshikaa-Saini)
- [Anushka Joshi](https://github.com/ajoshi30)
- [Anushka Kar](https://github.com/Anushka-kar)
- [Anushree Mehta](https://github.com/anushreemehta6)
- [Archisman Tarafdar](https://github.com/ArchismanT)
- [Aryan Karamtoth](https://github.com/spaciouscoder78)
- [Abhinendra Singh](https://github.com/singhabhinendra)
- [Anushree mehta](https://github.com/anushreemehta6)
- [Aryan Karamtoth](https://github.com/spaciouscoder78)
- [Argha Sen](https://github.com/ArghaSenn)
- [Amrutha](https://github.com/AmruthaPariprolu)
- [Ankitha R](https://github.com/Ankitha2130)
- Anishadevi
- [Anushka Joshi](https://github.com/ajoshi30)
- [Abhishek Agarwal](https://github.com/AbhiBab)
- [Aditi Kapil](https://github.com/Aditi31kapil)
- [Aksh Maheshwari](https://github.com/AkshMaheshwari)
- [Aryan Arora](https://github.com/AryanArora)
- [Ayan](https://github.com/Lighting-pixel)
- [Archita Aparajita Rath](https://github.com/archita-a1903)
- [Archit Srivastava](https://github.com/ArchitSr313)
- [Ananya Gupta](https://github.com/ananyag309)
- [AliGoodarzi-Ai](https://github.com/AliGoodarzi-Ai)
- [Ayan Mondal](https://github.com/trinetra110)
 - [Ankit Gupta](https://github.com/ankitgupta143) 
 -  [Astitv Bajpai](https://github.com/astitvabajpai)
 -  [Ashish Santani](https://github.com/ashishraja)
  | [`Back To Top`](#contents) |



- ### **B**


  - [Bhargav](https://github.com/BhargavTammana)

  - [Bhumika Gupta](https://github.com/bhumii-ka)
  -  [Bhanushri Chinta](https://github.com/bhanushri12)
- [Bhumika Bhatt](https://github.com/Bhumika1312)
- [Bharat Singh Parihar](https://github.com/bharat3645)
-[Bodisatwa Dutta](https://github.com/BDutta18)



| [`Back To Top`](#contents) |


- ### **C**

  - [Chandan Mahato](https://github.com/Mr-mahato)
  - [Chirag Sharma](https://github.com/chiragHimself)
  - [CH Shivangi](https://github.com/shivi13102)
  - [CoderXYZ14](https://github.com/CoderXYZ14/)
| [`Back To Top`](#contents) |
| [`Back To Top`](#https://github.com/Chelseasingla1) |


- ### **D**

  - [Deepak lumar shah](https://github.com/deepak9285)

  -[Dharani Neelapuram](https://github.com/Bhoomidhanu12)
  - [Dipesh Mittal](https://github.com/zeeno2616)


  - [Dasari Karthik Reddy](https://github.com/karthikreddydasari)
  - [Dovine K](https://github.com/dovineowuor)

  - [Debadittya Chatterjee](https://github.com/Deba-constructs)
  - [Debasis Sikdar](https://github.com/DebasisX)
  - [Dishi Malviya](https://github.com/dishi890)
  - [Devansh Ojha](https://github.com/Ojha8421)
  - [DorafinaTech](https://github.com/DorafinaTech)
  - [Dhruv Sahu](https://github.com/dhruvsahu611)
  
  | [`Back To Top`](#contents) |


- ### **E**
  - [Eunice Adewusi](https://github.com/eadewusic)
  - [Eshita Das](https://github.com/Edasgh)


| [`Back To Top`](#contents) |

- ### **F**

  - [Fenil Patel](https://github.com/fenil-ptl)

  - [Farhat Momin](https://github.com/farhattt-1203)
  - [Fahmitha Farhana](https://github.com/fah-04)
| [`Back To Top`](#contents) |

  
  | [`Back To Top`](#contents) |


- ### **G**

  - [Gssoc](https://github.com/GSS0C24)
  - [G Rutvik Sharma](https://github.com/Rutvik-121)
  - [Garvit](https://github.com/garvit-exe)
  - [Gaurav](https://github.com/Gaurav-576/)
  - [Greesma](https://github.com/Greesma-225B1)
  - [Goldy Patel](https://github.com/Goldypatel)
  
  | [`Back To Top`](#contents) |


  
- ### **H**
  - [Harshitha]((https://github.com/harshitha0004))
  - [Harsh Kumar Verma](https://github.com/realHKV)
   - [Harshita Pishwe](https://github.com/hpishwe)
- [Hamsika Krishnan Rapolu](https://github.com/Hamsikakrishnan)
- [Hem Raj](https://github.com/Hemraj-7)
- [Himangshu Sharma](https://github.com/HimangshuSharma01)
- [Hritika Sharan](https://github.com/hritika2409)
- [Harshita Joshi](https://github.com/harshita2303)
  | [`Back To Top`](#contents) |

- ### **I**

  - [Inam Yadav](https://github.com/INam1995)

  - [Ishika sah]( https://github.com/Ishika0-0)

  - [Ishan Kumar](https://github.com/ishankumax)
  - [Ishita Gupta](https://github.com/ishicodz)
  - [Itisha](https://github.com/itishacodes)
  - [Demo](https://github.com/demo)
  - [Isha](https://github.com/avogadroB)

    | [`Back To Top`](#contents) |



- ### **J**

  - [Japneet Kaur](https://github.com/Japneet001)

  - [Jayesh Pandey](https://github.com/jayeshpandey01)

 - [Jinam Sancheti](https://github.com/jinamsancheti)
  - [Jisha-TR](https://github.com/Jisha-tr)
  - [Janeesh](https://github.com/janeeshgithub)
  - [Jeba Rachel Nesica](https://github.com/Jeba-Rachel-Nesica)
    | [`Back To Top`](#contents) |



- ### **K**
  - [Khush Agrawal](https://github.com/Khushagrawal001)
  [Kirtan Soni](https://github.com/sonikirtan110)
  [Kittu Soni](https://github.com/kittu110)
 - [Kaushik Raj](https://github.com/KaushikBarnwal)
-  [Khushmita Kapoor](https://github.com/KhushmitaKapoor)

  -[Ketaki Chakraborty](https://github.com/ketaki-c)
  - [Kartik Gupta](https://github.com/anythingkartik)
  - [Kusum Desai](https://github.com/kusumdesai)
 - [kuldeep sharma](https://github.com/technicalkuldeep)
  - [khushi1315](https://github.com/khushi1315)
  - [Kruthi S B](https://github.com/kruthi-sb)
  - [Kartik Mehta](https://github.com/kartikmehta18)
  - [Kashish Arora](https://github.com/kash-1007)

| [`Back To Top`](#contents) |


- ### **L**

- [Likhith Mr](https://github.com/likhith-mr)

  - [Lovely Mahour](https://github.com/lovelymahor)
  - [Likhil N Maiya](https://github.com/lickhill)
  - [Lavany Sai Bollamreddi](https://github.com/lavanyasai-b)
  - [Laxmi Kandivalasa](https://github.com/laxmi47)

  | [`Back To Top`](#contents) |


- ### **M**

 - [Mitva Gami](https://github.com/MitvaGami)

  - [Meet Arora](https://github.com/meetarora10)

  - [Mohit Gupta](https://github.com/mtg718)

  -[Muskan Jodhani](https://github.com/muskan18113)
  - [Madhurima Roy](https://github.com/Madhurima-R04)
  - [Mukta Chaudhari](https://github.com/Mukta64Chaudhari)
  - [Mrityunjay Kumar](https://github.com/221fa04732)
  - [MuraliDharan](https://github.com/MuraliDharan7)
  - [Mahima](https://github.com/mahimakathpal)
  - [Maryam Mohamed Yahya](https://github.com/MaryamMohamedYahya)
  - [Mihir Phalke](https://github.com/mihirphalke1)
  - [Muhammad Shoaib Khan](https://github.com/msk21shoaib)
  - [MD REHAN](https://github.com/REHAN-18)
- [Meenal Saini](https://github.com/meenal900)

| [`Back To Top`](#contents) |



- ### **N**

    - [Sk Najir](https://github.com/najir83)
  - [`Nittin Balajee`](https://github.com/NittinBalajee1)
 - [Navya zitya](https://github.com/Navyazitya) 
  - [Naga](https://github.com/nagalakshmi08)
  - [Navjot Singh](https://github.com/navjot369)
 - [Nikhitha Reddy](https://github.com/nik-r-cmd)
 - [Nihar Ranjan Das](https://github.com/nihardas0611)
- [Navuluri Balaji](https://github.com/NavuluriBalaji)
- [Naman Jain](https://github.com/NamanJain795)
- [Niranjan Gaikwad](https://github.com/niranjansgitbuh)
- [Nitheesha](https://github.com/Nitheesha33)
- [Neeraj Sharma](https://github.com/neerajsharma897/)
- [Nidhi Kuntal](https://github.com/nidhi752)
- [Nisarg Shah](https://github.com/nisarg107/)
- [Nishant Dwivedi](https://github.com/nishant4500/)

| [`Back To Top`](#contents) |




- ### **O**

  - [Ojus](https://github.com/ojuss)

| [`Back To Top`](#contents) |

 - ### **P**

     - [Prajwal D P](https://github.com/prajwaldp223)

     - [Pearl Ochani](https://github.com/Pearlochani131677)

     - [Piyush Bagde](https://github.com/PiyushBagde)

    - [Prince Gupta](https://github.com/Princegupta101)

    - [Pranav Bansal](https://github.com/Prannav-Bansal)

    - [Pratham Vishwakarma](https://github.com/Pratham-Vishwakarma)



    - [Preeti Deora](https://github.com/Preeti-deora)


    - [Pranavi Mehta](https://github.com/pranavimehta13)


    - [Pranavi Srinivasula](https://github.com/Pranavi-04)

    - [Partha Sarathi Panda](https://github.com/PSP2706)

    - [Preethi Kamal](https://github.com/preethikamal)


    - [Pearl Vashistha](https://github.com/pearll12)

    - [Pavan Gowda T S](https://github.com/pavants777)

    - [Pryanshu Gupta](https://github.com/pryang007)


 

    - [Pranamya G Kulal](https://github.com/spacedust26)

    - [Prashant Anand](https://github.com/PrashantAnand03)
    - [Priyal_Adesara](https://github.com/priyaladesara)
    - [Puneet Tiwari](https://github.com/puneet426)
    - [Priyanshi Agrawal](https://github.com/PriyanshiAgr)
    - [Priyanshi Bhargava](https://github.com/Priyanshi0112)
    - [Priyanka Shanyal](https://github.com/Priyankasanyal04)
    - [Parimi Vedavalli](https://github.com/Veda273)
    - [Pushpa Vishwakarma](https://github.com/Pushpa472)
   
   | [`Back To Top`](#contents) |


- ### **Q**

 | [`Back To Top`](#contents) |

- ### **R**
  - [Rishita Rani](https://github.com/TechSenseiX)
  - [Rahuf khan](https://github.com/Rahufkhan)
  - [Ritika Sahu](https://github.com/Ritika-sahu)
  - [Riddhima Sharma](https://github.com/Riddhima-sh)
  - [Richa Dasila](https://github.com/richa-dasila)
  - [Riddhi](https://github.com/RiddhiMenroy)
  - [Rahul kumar](https://github.com/mrrahulkrr)
- [Rahul Sahu](https://github.com/rahuls49)
- [Roushan Verma](https://github.com/roushanverma23)
- [Rakshit](https://github.com/Rakshit-gen)
- [Rhea](https://github.com/rees8)
- [Rudransh Pratap Singh](https://github.com/CoderFleet)
- [Riya](https://github.com/Riya-221)
- [Rana Jay](https://github.com/RanaJay3101)
- [Ritik Singh](https://github.com/ritiksingh-01)
- [Ritik Sinha](https://github.com/RitikSinha04)
- [Riya Arora](https://github.com/riyaarora954)
- [Rohit Mukherjee](https://github.com/rickyrick23)
| [`Back To Top`](#contents) |



 - ### **S**

    -  [Sanjay](https://github.com/sanjay-kv)
    -  [Simanta Sarma](https://github.com/SimantaSarma)
    -  [Shadab](https://github.com/shadabalam78698)
    -  [Siva](https://github.com/dev-rsiva)
    - [Sanjay KV](https://github.com/sanjay-kv)
    - [Sahil M Patil](https://github.com/SAHILMPATIL)
    - [Sherin Baiju](https://github.com/sherinbaiju)
    - [Saisri Vishwanath](https://github.com/saisri0102)
    - [Shreyanshi Yadav](https://github.com/sshreyanshii)
    - [Shruti Sachan](https://github.com/shrutisachan08)
    - [Sai Tejaswani](https://github.com/SaiTejaswaniBikkasani)
    - [Samarasimha Reddy](https://github.com/samarasimhapeyala)
    - [Saswat Singh](https://github.com/saswat733)
    - [Sinchana](https://github.com/sinchana91)
    - [Swastik Giri](https://github.com/SwastikGiri)
    - [Sandip Dey](https://github.com/Helios-snd)
    - [Simra Tyagi ](https://github.com/siimrann)
    - [Swapnita Singh](https://github.com/Swapnita06) 
    - [Sujal Malhotra](https://github.com/sujal1256)
    - [Shivam Chauhan](https://github.com/Shivamm138)
    - [Soha Farhana](https://github.com/SohaFarhana)
    - [Sibam](https://github.com/Sibam-Paul)
    - [Sahil Singh](https://github.com/sahilsingh2002)
 - [Sai Manikanta Patro](https://github.com/SaiMani30)
 - [Saif ali](https://github.com/supersaif08)
 - [Sumit Kumar](https://github.com/07sumit1002)
- [Sasidharan V](https://github.com/Thewhitewolfsasi)
- [Swayam Takkamore](https://github.com/SwayamTakkamore)
- [Srilalitha](https://github.com/gantasrilaitha)
- [Sadath Hussain](https://github.com/sadath2001)
- [Samridha Das](https://github.com/Samridha0305)
- [Sanjana](https://github.com/sanjanaapandey)
- [Sanika Deokule](https://github.com/sanikadeokule)
- [Seersha](https://github.com/Seersha9802)
- [Shamayita Datta](https://github.com/shamayitadatta)
- [Shaik Hafiza](https://github.com/ShaikHafiza)
- [Shariq](https://github.com/Shariq2003)
- [Shashmitha](https://github.com/shashmitha46)
- [Shivathmika](https://github.com/shivathmikavemula)
- [Shreya Paul](https://github.com/shreya-paul-17)
- [Shuvojit Samanta](https://github.com/shuvojitss)
- [Sibangi Boxipatro](https://github.com/Sibangi-2911)
- [Simran Kukreja](https://github.com/Simran-0024/demo-try)
- [Sivani](https://github.com/ImmidiSivani)
- [Sk Sofiquee Fiaz](https://github.com/RandomSummer)
- [Sneha Giri](https://github.com/Snehagiri554)
- [Sridevi](https://github.com/Sridevi0321)
- [Sumalatha Salapu](https://github.com/SumaLatha2023)
- [Sumantrini Sarkar](https://github.com/Sumantrini48)
- [Suryansh Chourasia](https://github.com/Suryansh777777)


| [`Back To Top`](#contents) |



- ### **T**



  -  [Tanya Nagpal](https://github.com/Tanya-Nagpal)
  - [Tanish Rai](https://github.com/Tanish2510)

  - [T Rahul Prabhu](https://github.com/T-Rahul-prabhu-38)
  - [T.Manas](https://github.com/tmanas06)
  - [Teejay](https://github.com/teejay)
  - [Tanmay Deopurkar](https://github.com/tanmays62343)
  - [Tushar Bansal](https://github.com/Tusharb331)
  - [TR](https://github.com/TR)
  - [TR.1](https://github.com/TR)
 - [theritwik](https://github.com/theritwik)

  | [`Back To Top`](#contents) |



- ### **U**

- [uma](https://github.com/Uma-129)
  - [Utkarsh Gupta](https://github.com/Shadowsweep)

| [`Back To Top`](#contents) |

- ### **V**

  - [vishal-sharma-369](https://github.com/vishal-sharma-369)
  - [Vanshika](https://github.com/VanshikaSabharwal)
  - [Vanshika Pal](https://github.com/Vika0408)
  - [Vaishali](https://github.com/Vaishalic288)
  - [Vishal Maurya](https://github.com/vishalmaurya850)
  - [Vishvajeet](https://github.com/Vishvajeetr)
  - [Vishal Manve](https://github.com/vishalmanve)
  - [Varsha Pandian](https://github.com/varshapandiann)
  - [Varsha Dewangan](https://github.com/Varsha-1605)
  - [Vivek Rawat](https://github.com/vivekrawat21)
  - [Venkata Naga Gopal Varma Sagi](https://github.com/varma-101)
  - [Vedant Kale](https://github.com/VedantKale29)

| [`Back To Top`](#contents) |

- ### **W**


 | [`Back To Top`](#contents) |

- ### **X**

 
 | [`Back To Top`](#contents) |

- ### **Y**

  -  [Yashika Sharma](https://github.com/yashika1900)

 | [`Back To Top`](#contents) |


- ### **Z**

  - [Zoey](https://github.com/zoey-11)

  - |- [Zeba](https://github.com/zeba62) |
  
  | [`Back To Top`](#contents) |

## Our Pledge

We take participation in our community as a harassment-free experience for everyone and we pledge to act in ways to contribute to an open, welcoming, diverse and inclusive community.