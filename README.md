# Open-source-Practice
GSSoC is a 3-month long #OpenSource program by GirlScript Foundation, India.

## open-source-practice Pull Requests

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
  - [Aabhirup Paul](https://github.com/paul-abhirup)
  - [Anshika Saini](https://github.com/Anshikaa-Saini)
 -  [Anushree mehta](https://github.com/anushreemehta6)
| [`Back To Top`](#contents) |

- ### **B**
  - [Bharat Singh Parihar](https://github.com/bharat3645)
| [`Back To Top`](#contents) |

- ### **C**
  - 
| [`Back To Top`](#contents) |

- ### **D**
  - [Dipesh Mittal](https://github.com/zeeno2616)
| [`Back To Top`](#contents) |

- ### **E**
  - 
| [`Back To Top`](#contents) |

- ### **F**
  - 
| [`Back To Top`](#contents) |

- ### **G**
  - [Gauri](https://github.com/gauribahuguna21)
| [`Back To Top`](#contents) |

- ### **H**
  - 
| [`Back To Top`](#contents) |


- ### **I**
  - [Inam Yadav](https://github.com/INam1995)
| [`Back To Top`](#contents) |

- ### **J**
  - 
| [`Back To Top`](#contents) |

- ### **K**
  - 
| [`Back To Top`](#contents) |

- ### **L**
  - 
| [`Back To Top`](#contents) |

- ### **M**
  - 
| [`Back To Top`](#contents) |

- ### **N**
  - 
| [`Back To Top`](#contents) |

- ### **O**
  - 
| [`Back To Top`](#contents) |

 - ### **P**
     - [Piyush Bagde](https://github.com/PiyushBagde)
    - [Prince Gupta](https://github.com/Princegupta101)
    - [Pratham Vishwakarma](https://github.com/Pratham-Vishwakarma)
    - [Pavan Gowda T S](https://github.com/pavants777)
 
| [`Back To Top`](#contents) |

- ### **Q**
  - 
| [`Back To Top`](#contents) |

- ### **R**
  - 
| [`Back To Top`](#contents) |

 - ### **S**
    -  [Sanjay](https://github.com/sanjay-kv)
   
| [`Back To Top`](#contents) |

- ### **T**
  - [Teejay](https://github.com/teejay)
| [`Back To Top`](#contents) |

- ### **U**
  - 
| [`Back To Top`](#contents) |

- ### **V**
  - 
| [`Back To Top`](#contents) |

- ### **W**
  - 
| [`Back To Top`](#contents) |

- ### **X**
  - 
| [`Back To Top`](#contents) |

- ### **Y**
  - 
| [`Back To Top`](#contents) |

- ### **Z**
  - 
| [`Back To Top`](#contents) |
## Our Pledge

We take participation in our community as a harassment-free experience for everyone and we pledge to act in ways to contribute to an open, welcoming, diverse and inclusive community.


