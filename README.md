
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

  - [Ayush Singh](https://github.com/AyushSinghRajput1366)
  - [Aabhirup Paul](https://github.com/paul-abhirup)
  - [Anshika Saini](https://github.com/Anshikaa-Saini)
  - [Anushree mehta](https://github.com/anushreemehta6)
  - [Aryan Karamtoth](https://github.com/spaciouscoder78)
  - [Afzal Hassan](https://github.com/iemafzalhassan)
  - [Amrutha](https://github.com/AmruthaPariprolu)
  - [Anushree mehta](https://github.com/anushreemehta6)
- [Aabhirup Paul](https://github.com/paul-abhirup)
- [Aakruti Kalia](https://github.com/akku-07)
- [Abhay S N](https://github.com/Abhay182005dat)
- [Abdul](https://github.com/abd0777)
- [Aditi Kapil](https://github.com/Aditi31kapil)
- [Aditi Tapariya](https://github.com/adititapariya)
- [Aditya Anand](https://github.com/shivam2027)
- [Ajay Patidar](https://github.com/Ajay-patidar0)
- [Akash Nema](https://github.com/Akash-nema)
- [Aksh Maheshwari](https://github.com/AkshMaheshwari)
- [Akshat Jain](https://github.com/its-AkshatJain)
- [Amarta Waghani](https://github.com/Amarta113)
- [Amrutha](https://github.com/AmruthaPariprolu)
- [Ankan Mukhopadhyay](https://github.com/Peart-Guy)
- [Anmol Purwar](https://github.com/anmol-2004)
- [Anshika Saini](https://github.com/Anshikaa-Saini)
- [Anuj Chaudhary](https://github.com/Anuj054)
- [Anushka Joshi](https://github.com/ajoshi30)
- [Anushka Kar](https://github.com/Anushka-kar)
- [Anushka Pote](https://github.com/Anushka-Pote)
- [Anushree Mehta](https://github.com/anushreemehta6)
- [Anushree Nair](https://github.com/anushreenair)
- [Archisman Tarafdar](https://github.com/ArchismanT)
- [Aryan Karamtoth](https://github.com/spaciouscoder78)
- [Asha Rani Satpathy](https://github.com/AshaSatpathy08)
- [Atmakuri Manoj Kumar](https://github.com/Manojkumar1007)
- [Avantika Ajit](https://github.com/av0422)
- [Ayushi Baijal](https://github.com/ABaijal9)
- [Aabhirup Paul](https://github.com/paul-abhirup)
- [Aakruti Kalia](https://github.com/akku-07)
- [Abankita Behera](https://github.com/Abankita)
- [Abhishek Agarwal](https://github.com/AbhiBab)
- [Aditi Kapil](https://github.com/Aditi31kapil)
- [Ajay Patidar](https://github.com/Ajay-patidar0)
- [Aksh Maheshwari](https://github.com/AkshMaheshwari)
- [Amarta Waghani](https://github.com/Amarta113)
- [Amrutha](https://github.com/AmruthaPariprolu)
- [Ankan Mukhopadhyay](https://github.com/Peart-Guy)
- [Anshika Saini](https://github.com/Anshikaa-Saini)
- [Anushka Joshi](https://github.com/ajoshi30)
- [Anushka Kar](https://github.com/Anushka-kar)
- [Anushka Pote](https://github.com/Anushka-Pote)
- [Anushree Mehta](https://github.com/anushreemehta6)
- [Archisman Tarafdar](https://github.com/ArchismanT)
- [Aryan Karamtoth](https://github.com/spaciouscoder78)
- [Avantika Ajit](https://github.com/av0422)
 -  [Anushree mehta](https://github.com/anushreemehta6)
  - [Aryan Karamtoth](https://github.com/spaciouscoder78)
  - [Ajay Pratap Tomar](https://github.com/ajayprataptomar)
  - [Akshit Padha](https://github.com/vaxxnsh)
  - [Anurag Kumar](https://github.com/AnuragKr24)
  - [Ayush Kumar](https://github.com/codebreaker3008)
  - [Arunava](https://github.com/CapAru)
  - [Amrutha](https://github.com/AmruthaPariprolu)
  - [Anushka Joshi](https://github.com/ajoshi30)
  - [Abhishek Agarwal](https://github.com/AbhiBab)
  - [Aditi Kapil](https://github.com/Aditi31kapil)
  - [Aksh Maheshwari](https://github.com/AkshMaheshwari)
  - [Abhinendra Singh](https://github.com/singhabhinendra)
   - [Akash Gupta](https://github.com/Akash-Gupta-git)
  - [Abu Bakar](https://github.com/abubakarp789)
  - [Ayoush Kumar](https://github.com/ayoush-kumar)
  - [Arati Ambekar](https://github.com/AratiAmbekar)
  - [Amrit Raj Thakur](https://github.com/Amrit-Raj-17)
 -  [Anushree mehta](https://github.com/anushreemehta6)
 -  [Abhilasha Kamal](https://github.com/abhi-la-sha)
 -  [Aditya Prakash](https://github.com/AdityaPrakash-03)
 -  [Anish Singh Chandel](https://github.com/ChandelAnish)
 -  [Akshay](https://github.com/AkshayKankaria)
  -  [Aniruddha Rawool](https://github.com/rawani123)
 -  [Aishwarya_Kadarla](https://github.com/Aishwaryaa-22)
 -  [Asha Jyothi](https://github.com/Asha0509)
 -  [Ananya Singh](https://github.com/Ananya-Singh1901)
 -  [Aditi Gupta](https://github.com/Aditi-Gupta-dev)
 -  [Aindrela Saha](https://github.com/aindrelasaha)
 -   [Ayushi Pathak](https://github.com/Ayushi22-coder)
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
- [Ashutosh Rath](https://github.com/GitGudScrubss)
- [Ayan](https://github.com/Lighting-pixel)
- [Archita Aparajita Rath](https://github.com/archita-a1903)
- [Ananya G Shetty](https://github.com/Ananyashetty7)
- [Archit Srivastava](https://github.com/ArchitSr313)
- [Ananya Gupta](https://github.com/ananyag309)
- [AliGoodarzi-Ai](https://github.com/AliGoodarzi-Ai)
- [Ayan Mondal](https://github.com/trinetra110)
 - [Ankit Gupta](https://github.com/ankitgupta143) 
 -  [Astitv Bajpai](https://github.com/astitvabajpai)
 -  [Ashish Santani](https://github.com/ashishraja)
 -  [Akulla Mudunuri](https://github.com/22wh1a12a4)
 -  [Amrutha Gogireddy](https://github.com/amrutha1215)




  | [`Back To Top`](#contents) |


- ### **B**
  - [Benak Deepak](https://github.com/benakdeepak)
  - [Bharat Singh Parihar](https://github.com/bharat3645)
  - [Bharath](https://github.com/bharath200415/)
  - [Bhargav](https://github.com/BhargavTammana)
  - [Bhumika Gupta](https://github.com/bhumii-ka)
  -  [Bhanushri Chinta](https://github.com/bhanushri12)
- [Bhumika Bhatt](https://github.com/Bhumika1312)
- [Bharat Singh Parihar](https://github.com/bharat3645)
-[Bodisatwa Dutta](https://github.com/BDutta18)
-[Bhanusri Viswanadhapalli](https://github.com/VBhanusr)

| [`Back To Top`](#contents) |


- ### **C**
  - [Chalsi Jain] (https://github.com/Chelsea67jain)
  - [Chalsi Jain](https://github.com/Chelsea67jain)
  - [Chanmeet Kaur](https://github.com/chanmeet01)
  - [Chandan Mahato](https://github.com/Mr-mahato)
  - [Chirag Sharma](https://github.com/chiragHimself)
  - [CH Shivangi](https://github.com/shivi13102)
  - [CoderXYZ14](https://github.com/CoderXYZ14/)
  - [Chelsea](https://github.com/Chelseasingla1)

| [`Back To Top`](#contents) |


  - ### **D**

  - [Deepak lumar shah](https://github.com/deepak9285)

  -[Dharani Neelapuram](https://github.com/Bhoomidhanu12)
  - [Dipesh Mittal](https://github.com/zeeno2616)
  - [Mohammad Danish](https://github.com/Danish0703)
  - [Divya Gupta](https://github.com/DG8131)
  - [Dhanashree Patil](https://github.com/Dhanashree170)
  - [Dipti Prangya Sahoo](https://github.com/dipti-019)
  - [Dushyant Bhutiyani](https://github.com/dushyant2909)
  - [Dharani](https://github.com/Dharanilakkireddy)

  - [Dev Patel](https://github.com/DevPatel1023)
    
  - [Devendra Verma](https://github.com/KDevendra)


  - [Divyadharshini R](https://github.com/d1vyadharsh1n1)
  - [Disha Agrawal](https://github.com/disha3110)
  - [Dishika Vaishkiyar](https://github.com/Dishika18)
  - [Dasari Karthik Reddy](https://github.com/karthikreddydasari)
  - [Dovine K](https://github.com/dovineowuor)

  - [Debadittya Chatterjee](https://github.com/Deba-constructs)
  - [Debasis Sikdar](https://github.com/DebasisX)
  - [Dishi Malviya](https://github.com/dishi890)
  - [Dakshata Mishra](https://github.com/daky2024)
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
  - [Gauri](https://github.com/gauribahuguna21)
  - [Gssoc](https://github.com/GSS0C24)
  - [Gopikrishnan](https://github.com/gopi-trip)
  - [G Rutvik Sharma](https://github.com/Rutvik-121)
  - [Gaurav](https://github.com/Gaurav-576/)
  - [Greesma](https://github.com/Greesma-225B1)
  - [Goldy Patel](https://github.com/Goldypatel)
  
  | [`Back To Top`](#contents) |


- ### **H**

  -[Hardik Tripathi](https://github.com/HardikTripathi04)
  -  [Himanshu](https://github.com/HE-MAN-22603) 
  -[Harshini S](https://github.com/Harshini2015) 
 - [Himanshu Saini](https://github.com/psjhimanshu)
 - [Hritika Sharan](https://github.com/hritika2409)
  - [Haritha](https://github.com/harithaguna)
  - [Himanshi](https://github.com/Himanshityagii24)
  - [Harleen kaur](https://github.com/Harleen-786)
    - [Hitanshu Kumar Singh](https://github.com/hitanshu04)
 - [Hema Sree](https://github.com/Hemav009)
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

  - [Isha Prajapati](https://github.com/ishap11)
  - [Ishitva Joshi](https://github.com/Ishitva744)
  - [Ishaan Karmakar](https://github.com/ISHAAN-KKR)
  - [Ishika sah]( https://github.com/Ishika0-0)
  - [Ishan Kumar](https://github.com/ishankumax)
  - [Ishita Gupta](https://github.com/ishicodz)
  - [Itisha](https://github.com/itishacodes)
  - [Demo](https://github.com/demo)
  - [Isha](https://github.com/avogadroB)
  - [Irtesaam Atfi](https://github.com/irtesaam)

    | [`Back To Top`](#contents) |




- ### **J**

  -[jayashree behera](https://github.com/Jayashree-04)

  - [Jansi Sabharwal](https://github.com/JansiSabharwal05)
  - [Jyotsna Singh](https://github.com/Akki-58)
- [Jyothsna](https://github.com/JyothsnaThangudu) |
  - [Japneet Kaur](https://github.com/Japneet001)

  - [Jayesh Pandey](https://github.com/jayeshpandey01)

 - [Jinam Sancheti](https://github.com/jinamsancheti)
  - [Jisha-TR](https://github.com/Jisha-tr)

  - [Jeet Das](https://github.com/JeetDas5)

  - [Tanisha Bansal](https://github.com/TanishaBansal101)
  - [Janeesh](https://github.com/janeeshgithub)
  - [Jeba Rachel Nesica](https://github.com/Jeba-Rachel-Nesica)
    | [`Back To Top`](#contents) |


- ### **K**

  - [Khushbu Jain](https://github.com/khushbujain41709)

  - [Kulashekar Inkollu](https://github.com/Kulashekar01)
  - [Keertana](https://github.com/kskeertana)
  - [khurshed07](https://github.com/khurshed07)
  - [https://github.com/khurshed07](https://github.com/khurshed07)
  - [https://github.com/khurshed07](https://github.com/khurshed07)
  - [Khushi Kunte](https://github.com/khushikunte)
  -[Kesri N Shukla](https://github.com/kesri9211) 
  -[Kashif](https://github.com/Kashif581)
  -  [Kalamatha Eshwari](https://github.com/Kalamatha-Eshwari)
   - [Kshitija Giradkar](https://github.com/KshitijaGiradka)
  - [Khushi Upadhyay](https://github.com/khushi-upadhyay)
  - [Karthik](https://github.com/kartheekmule)
  - [Kushal Gupta](https://github.com/khush200145)
  - [Khushi Khurana](https://github.com/khushikhuranaa2)
  - [Kwinsi Thakkar](https://github.com/22bce355)
  - [Kanishk Jain](https://github.com/Kanishk-03-Jain)
- [KOLLI SRI KRISHNA KARTHIKEYA](https://github.com/KARTHIK174)
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
  - [KAVYA SRI GOPIREDDY](https://github.com/Kavyasrigopireddy)

| [`Back To Top`](#contents) |



- ### **L**

      -[Lalith Kumar Allu](https://github.com/LalithKumar77)
 - [Likhith Mr](https://github.com/likhith-mr)

  - [Lovely Mahour](https://github.com/lovelymahor)
  - [Likhil N Maiya](https://github.com/lickhill)
  - [Lavany Sai Bollamreddi](https://github.com/lavanyasai-b)
  - [Laxmi Kandivalasa](https://github.com/laxmi47)

  | [`Back To Top`](#contents) |



- ### **M**

  - [Menka](https://github.com/codewithishu)
  - [Muskaan](https://github.com/MuskaanMohta)
-[Musfiraa](https://github.com/Mooosiee) |
  - [Moutama Rakshit](https://github.com/moutamarakshit) 
  - [Muhammad Baqir](https://github.com/mb-aarfi)
- [Maddu Harshitha](https://github.com/MadduHarshitha30) |

  - [Madhuri](https://github.com/Madhuri36)
- [Mitul Dwivedi](https://github.com/Mitul1927)
  - [Mrigaank Jaswal ](https://github.com/Mrigaank-9)
-[`Manya`](https://github.com/DownOnCoffee) |
 - [Mohit Solanki](https://github.com/mohit2202solanki)
  -  [Mukul Rajput](https://github.com/MUKUL-RAJPUT2004)

  - [Mohit](https://github.com/Mohitgit22)

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
  - Mihir Phalke (https://github.com/mihirphalke1)
  - [Macha Varshitha](https://github.com/Varshitha713)
  - [Mihir Phalke](https://github.com/mihirphalke1)
  - [Muhammad Shoaib Khan](https://github.com/msk21shoaib)
  - [MD REHAN](https://github.com/REHAN-18)
- [Meenal Saini](https://github.com/meenal900)

| [`Back To Top`](#contents) |

- ### **N**

  -   [Nihal Somarajupalli](https://github.com/Nihal-Somarajupalli)
  - [Nikita](https://github.com/nikkittaa)
  - [Neeraja](https://github.com/NeerajaGurram)
  - [Naincy Kumari](https://github.com/Naincy04)
  - [Nikitha Kandi](https://github.com/nikitha-kandi)
- [Natasha Kushwah](https://github.com/Natasha-kush) 
  - [Navjot singh](https://github.com/NAVJOT-786)
  - [Nimai Barman](https://github.com/b-nimai)
 - [Nancy Varyani](https://github.com/nancyvaryani)
  - [Sk Najir](https://github.com/najir83)
  - [`Nittin Balajee`](https://github.com/NittinBalajee1)
 - [Navya zitya](https://github.com/Navyazitya) 
  - [Naga](https://github.com/nagalakshmi08)
  - [Nandini Sain](https://github.com/nsain25) 
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
 - [Nimisha Mavar](https://github.com/Nimisha-Mavar)

| [`Back To Top`](#contents) |



- ### **O**

  - [Ojus](https://github.com/ojuss)

| [`Back To Top`](#contents) |

 - ### **P**

     - [Pavan Gowda T S](https://github.com/pavants777)
     - [Piyush Bagde](https://github.com/PiyushBagde)
     - [Pragya Kumari] (https://github.com/pragyamyra)
     - [Pratham Vishwakarma](https://github.com/Pratham-Vishwakarma)
    - [Prince Gupta](https://github.com/Princegupta101)

     - [Payal Kumari](https://github.com/PayalKumari10)
     - [PRANSHU CHAURASIA](https://github.com/MrPC7)
     - [Prajwal D P](https://github.com/prajwaldp223)
     - [Pearl Ochani](https://github.com/Pearlochani131677)

     - [Piyush Bagde](https://github.com/PiyushBagde)

     - [demo](https://github.com/demo)
    - [Prince Gupta](https://github.com/Princegupta101)

    - [prudhvi](https://github.com/Prudhvi-232)
    - [Pranav Bansal](https://github.com/Prannav-Bansal)
    - [Pratham Vishwakarma](https://github.com/Pratham-Vishwakarma)

    - Pragya Singh(https://github.com/Woookiiee) 

    - [Preeti Deora](https://github.com/Preeti-deora)

    - [Pranavi Mehta](https://github.com/pranavimehta13)

    - [Pranavi Srinivasula](https://github.com/Pranavi-04)

    - [Partha Sarathi Panda](https://github.com/PSP2706)

    - [Preethi Kamal](https://github.com/preethikamal)
    - [Pearl Vashistha](https://github.com/pearll12)
    - [Pavan Gowda T S](https://github.com/pavants777)
    - [Prakhar Khandelwal](https://github.com/Prakharkhandelwal02)
    - [Prajwal kumar](https://github.com/prajwal9773)
    -  [Pranali Modi](https://github.com/Pranali3103) 
    - [Prayag Chavan](https://github.com/PRAYAG0908)
     - [Pallavi Gudupalli](https://github.com/PallaviGudupallavi)
    - [Priyanka Lama](https://github.com/Unalia09)
    - [Prateek Agrawal](https://https://github.com/Prateek0305)
    - [pragnapadamata](https://github.com/pragnapadamata)
    - [Peehu Mishra](https://github.com/Peehu1308)
    - [Pryanshu Gupta](https://github.com/pryang007)
    - [Pranamya G Kulal](https://github.com/spacedust26)
    - [Prashant Anand](https://github.com/PrashantAnand03)
    - [Priyal_Adesara](https://github.com/priyaladesara)
    - [Puneet Tiwari](https://github.com/puneet426)
    - [Prabhjot Singh](https://github.com/Prabh-84)
    - [Priyanshi Agrawal](https://github.com/PriyanshiAgr)
    - [Priyanshi Bhargava](https://github.com/Priyanshi0112)
    - [Priyanka Shanyal](https://github.com/Priyankasanyal04)
    - [Parimi Vedavalli](https://github.com/Veda273)
    - [Pushpa Vishwakarma](https://github.com/Pushpa472)
    - [Padmasree Sangani](https://github.com/PadmasreeSangani)
    - [Pallavi Mukalla](https://github.com/Pallavi-Mukalla)
   
   | [`Back To Top`](#contents) |


- ### **Q**

 | [`Back To Top`](#contents) |


- ### **R**

  -  [Rahul Yadav](https://github.com/rahul-2004-json)
  - [Rama](https://github.com/ramajaiswal08)
- [Rakshit](https://github.com/Rakshit-gen)
- [Rana Jay](https://github.com/RanaJay3101)
- [Ranjan Kumar Pandit](https://github.com/Ranj8521Kumar)
- [Rees8 (Rhea)](https://github.com/rees8)
- [Ritik Sinha](https://github.com/RitikSinha04)
- [Ritik Singh](https://github.com/ritiksingh-01)
- [Riya](https://github.com/Riya-221)
- [Riya Arora](https://github.com/riyaarora954)
- [Rudransh Pratap Singh](https://github.com/CoderFleet)


  - [Ravindra Kumar](https://github.com/Ravindrak0812) 
  - [Rohit](https://github.com/MrCodYrohit)
  - [Rajneesh Kumar Arya]([#content](https://github.com/Rajneeshkarya) 
- [Rishmita](https://github.com/rishmiiee26)
- [RadhaRashmitha Jujjavarapu](https://github.com/rashmitha155)
  - [Rizwan Ahmad](github.com/Rizwanahmad07)
  - [Rishita Chourey](https://github.com/RishitaChourey)
   - [Rahul](https://github.com/Sadhvika55)

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
- [Riya Sudrik](https://github.com/jigglypufflazybaby)

| [`Back To Top`](#contents) |




 - ### **S**

    -  [Salman Ahmed](https://github.com/salmanahmed-chd)
    -  [Sanjay](https://github.com/sanjay-kv)
    -  [Sonali](https://github.com/Sammandy)
    -  [Shobit](https://github.com/shobit000)
    -  [Sanskar](https://github.com/SanskarShrivastava)
    - [Sayantan Saha](https://github.com/Sayantan1024)
    - [Sneha Giri](https://github.com/Snehagiri554)
    -  [Saketh Surya](https://github.com/saketh-05)
    - [Sitambhra](https://github.com/Sitambhra02)
    - [Shivathmika ](https://github.com/shivathmikavemula)
    - [Shamayita Datta](https://github.com/shamayitadatta)
    - [Sanjay](https://github.com/sanjay-kv)
    - [Seersha](https://github.com/Seersha9802)
    - [Sivani](https://github.com/ImmidiSivani)
    - [Shreya Paul](https://github.com/shreya-paul-17)
    - [Sadath Hussain](https://github.com/sadath2001)
    - [Sadath Hussain.2](https://github.com/sadath2001)
    - [Sk Asraful](https://github.com/iamasraful)
    - [SatyaD012](https://github.com/SatyaD012)
    - [Sahithi](https://github.com/sahithialeti)
    - [Suhitha](https://github.com/suhitha02)
    - [Sobhit Singhal](https://github.com/sobhitsinghal)
    - [Somya Saxena](https://github.com/somyasaxena01)
    - [Sayan Maity](https://github.com/Sayanmaity2003)
    - [Shubhangi](https://github.com/Shubh-88)
  - [Sneha Sahu](https://github.com/snehasahu7)
   - [Shivarathri Jayanth Rahul](https://github.com/761jayanth8)
    -[shivanshu kumar srivastava](https://github.com/githubshivanshukumarsrivastava)
    - [Shiraptinath C R](https://github.com/Shirapti-nath)
    - [Sadhvika](https://github.com/Sadhvika55)
    -  [Sanjay](https://github.com/sanjay-kv)
    -  [Siddhima De](https://github.com/siddhima22)
    -  [Shreeyansh](https://github.com/SHREEYANSH764)
    -  [Swata Swayam Dash](https://github.com/swataswayam-14)
    -  [Sudhish](https://github.com/Sudhish23)
    -  [Sagar](https://github.com/Unknownmaster0)
    -  [Sonali](https://github.com/Sammandy)
     -  [Sai Kuladeep](https://github.com/saikuladeepgithub)
     -  [Sauravi Sar](https://github.com/SarthVader2004)
    -  [Sharitha](https://github.com/SHARITHA2002)
    -  [Siwani](https://github.com/Siwanikaushik)
    -  [Sneha S](https://github.com/MavSneha)
    -  [Shreya Bagchi](https://github.com/BagchiShreya)
    -  [Sai Madhuri](https://github.com/Madhuri36)
    -  [Sanya](https://github.com/s4sanyaa)
    -   [Satya](https://github.com/satyaveni299)
    -  [Saumya](https://github.com/saumyajainnn)
    -  [Siddharth](https://github.com/gunner26735)
    -  [Somya Aggarwal](https://github.com/SomyaAggarwal1209)
    -  [Sree](https://github.com/Sree)
     -  [Skand Singh](https://github.com/SkandSingh)
    -  [Suhaina Fathima M](https://github.com/SuhainaFathimaM)
    -  [Saumya](https://github.com/SaumyaSinha11)
      -  [Simanta Sarma](https://github.com/SimantaSarma)
    -  [Shadab](https://github.com/shadabalam78698)
    -  [Siva](https://github.com/dev-rsiva)
    - [Sanjay KV](https://github.com/sanjay-kv)
    - [Sandeep Garai](https://github.com/sandeep-garai)
     - [Shagun](https://github.com/gitshott)
    - .[Sandhyarani](https://github.com/Sandhyarani23)
   - [Sudiksha18](https://github.com/Sudiksha18)
    - [Samriddha Halder](https://github.com/Samriddha49)
   - [Sahil M Patil](https://github.com/SAHILMPATIL)
    - [Sherin Baiju](https://github.com/sherinbaiju)
    - [Saisri Vishwanath](https://github.com/saisri0102)
    - [Shreyanshi Yadav](https://github.com/sshreyanshii)
    - [Shruti Sachan](https://github.com/shrutisachan08)
    - [Sai Tejaswani](https://github.com/SaiTejaswaniBikkasani)
    - [Samarasimha Reddy Peyala](https://github.com/samarasimhapeyala)
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
- [Shriya Dindi](https://github.com/shriyadindi)
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
- [Sanjana Davuluri](https://github.com/it221291)

| [`Back To Top`](#contents) |

- ### **T**

  - [Tanishq Singh](https://github.com/singhtanishq)
  -  [Tanya Nagpal](https://github.com/Tanya-Nagpal)
  - [Tanish Rai](https://github.com/Tanish2510)
  - [T Rahul Prabhu](https://github.com/T-Rahul-prabhu-38)
  - [T.Manas](https://github.com/tmanas06)
  - [Teejay](https://github.com/teejay)
  - [Teja Kumar](https://www.github.com/TejaKumar123)
  - [Tuba Khan](https://github.com/tubakhxn)
 - [Tanaya](https://github.com/Tanaya-1-2-3)
  - [Tanisha](https://github.com/tanisha290)

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
  -  [Vatsal](https://github.com/Vatsal-D07)
  - [Vaishali](https://github.com/Vaishali-ajmera)
- [vaidehi](https://github.com/vaidehi134) |
- [Viraj]([https://github.com/Virucodes) |
  - [Varun Allagh](https://github.com/varunallagh21022002)
  - [Varshini.E](https://github.com/Varshini0703)
  - [Vanisha Gupta](https://github.com/V-anisha)
- [VarshaYadav](https://github.com/rainybug11)
- [Virendra](https://github.com/virenK0211)) |
  - [Varshitha YS](https://github.com/Varshithays)
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
  - [Vedant Patel](https://github.com/vedant3337)

| [`Back To Top`](#contents) |



- ### **W**


 | [`Back To Top`](#contents) |

- ### **X**

- 
| [`Back To Top`](#contents) |

- ### **Y**

  -  [Yeshaswi](https://github.com/yp9435)
  -  [YASHIKA KEDIA](https://github.com/yashikakedia) |

-[YASH_SRIVASTAVA](https://github.com/yash21sriv) |
  - [Yash Tyagi](https://github.com/yash-tyagi-2003)
  - [Yashika Garg](https://github.com/yashi-025)
  - [Yatin Sabikhi](https://github.com/Yatin-Sabikhi)
  -  [Yashika Sharma](https://github.com/yashika1900)
  - [Yashika Goyal](https://github.com/yashika-45/)
  -  [Yashvi Goyal](https://github.com/yg2505)
  | [`Back To Top`](#contents) |



- ### **Z**

  - [Zoey](https://github.com/zoey-11)

  - |- [Zeba](https://github.com/zeba62) |
  
  | [`Back To Top`](#contents) |

## Our Pledge

We take participation in our community as a harassment-free experience for everyone and we pledge to act in ways to contribute to an open, welcoming, diverse and inclusive community.
