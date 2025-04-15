# Beginning JS LWHH
This is JS practice Repo to pratice JS from anywhere.
Tutorial by Hasin Hayder @ Youtube will be followed, another resource will be howtocode.dev in bangla.
Let's try to have fun with JS!!	

# কিভাবে কাজ করা হচ্ছে?
রিসোর্স হিসেবে ব্যবহৃত হচ্ছে হাসিন হায়দারের ইউটিউব ভিডিওসমূহ।
লিংক:
- [ ] [Beginner's JS](https://www.youtube.com/playlist?list=PLoR56CteKZnAdVtfTbAbUqT2thG4S-Anv)
- [ ] [বই- মারহাবা জাভাস্ক্রিপ্টে মারো থাবা - ঝংকার মাহবুব](https://www.rokomari.com/book/455936/marhaba-javascripte-maro-thaba)

# কোড চর্চা
প্রাথমিকভাবে ব্যবহৃত হবে Notepad++
বারবার ব্রাউজার বা প্রসেস এর ঝামেলা এড়াতে Notepad++ এ কোড করেই সেখানেই কোড এক্সিকিউশন করা হবে।
এইজন্য লাগবে নিচের দুইটা প্লাগিন।
১. jN Notepad++ => Emmet এর কাজ করবে।
২. Npp Exec => Node.js ইন্সটল করে সেটার এক্সিকিউশন ব্রাউজার ছাড়াই Notepad++ এ করবে।
৩. Explorer => Notepad++ এ বসে ফাইল তৈরি, রিনেম ও হ্যান্ডেলিং এর কাজ করা।

Npp Exec এর জন্য যে কমান্ড লাগে সেটা নিম্মরূপ:
```
cd $(CURRENT_DIRECTORY)
node $(FILE_NAME)
```
আর সবগুলো ডিভাইস থেকে এই রিপোজিটরিতে Push করা হবে। গিটের জন্য জন্য কমান্ড নিম্মরূপ:
 ssh-keygen -t ed25519 (ssh জেনারেট করার জন্য ) 
  বিস্তারিত- 
  - [ ] [SSH Gen](https://docs.gitlab.com/ee/user/ssh.html)

Repo Push 

```  
 git push --set-upstream git@gitlab.com:efthaqur/beginning-js-lwhh.git main
 ```
```
---------------------------------------------
```


## Add your files

- [ ] [Create](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#create-a-file) or [upload](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#upload-a-file) files
- [ ] [Add files using the command line](https://docs.gitlab.com/ee/gitlab-basics/add-file.html#add-a-file-using-the-command-line) or push an existing Git repository with the following command:

```
cd existing_repo
git remote add origin https://gitlab.com/efthaqur/beginning-js-lwhh.git
git branch -M main
git push -uf origin main
```

## Integrate with your tools

- [ ] [Set up project integrations](https://gitlab.com/efthaqur/beginning-js-lwhh/-/settings/integrations)

## Collaborate with your team

- [ ] [Invite team members and collaborators](https://docs.gitlab.com/ee/user/project/members/)
- [ ] [Create a new merge request](https://docs.gitlab.com/ee/user/project/merge_requests/creating_merge_requests.html)
- [ ] [Automatically close issues from merge requests](https://docs.gitlab.com/ee/user/project/issues/managing_issues.html#closing-issues-automatically)
- [ ] [Enable merge request approvals](https://docs.gitlab.com/ee/user/project/merge_requests/approvals/)
- [ ] [Set auto-merge](https://docs.gitlab.com/ee/user/project/merge_requests/merge_when_pipeline_succeeds.html)

## Test and Deploy

Use the built-in continuous integration in GitLab.

- [ ] [Get started with GitLab CI/CD](https://docs.gitlab.com/ee/ci/quick_start/index.html)
- [ ] [Analyze your code for known vulnerabilities with Static Application Security Testing (SAST)](https://docs.gitlab.com/ee/user/application_security/sast/)
- [ ] [Deploy to Kubernetes, Amazon EC2, or Amazon ECS using Auto Deploy](https://docs.gitlab.com/ee/topics/autodevops/requirements.html)
- [ ] [Use pull-based deployments for improved Kubernetes management](https://docs.gitlab.com/ee/user/clusters/agent/)
- [ ] [Set up protected environments](https://docs.gitlab.com/ee/ci/environments/protected_environments.html)

***

# Editing this README

When you're ready to make this README your own, just edit this file and use the handy template below (or feel free to structure it however you want - this is just a starting point!). Thanks to [makeareadme.com](https://www.makeareadme.com/) for this template.

## Suggestions for a good README

Every project is different, so consider which of these sections apply to yours. The sections used in the template are suggestions for most open source projects. Also keep in mind that while a README can be too long and detailed, too long is better than too short. If you think your README is too long, consider utilizing another form of documentation rather than cutting out information.

## Name
Choose a self-explaining name for your project.

## Description
Let people know what your project can do specifically. Provide context and add a link to any reference visitors might be unfamiliar with. A list of Features or a Background subsection can also be added here. If there are alternatives to your project, this is a good place to list differentiating factors.

## Badges
On some READMEs, you may see small images that convey metadata, such as whether or not all the tests are passing for the project. You can use Shields to add some to your README. Many services also have instructions for adding a badge.

## Visuals
Depending on what you are making, it can be a good idea to include screenshots or even a video (you'll frequently see GIFs rather than actual videos). Tools like ttygif can help, but check out Asciinema for a more sophisticated method.

## Installation
Within a particular ecosystem, there may be a common way of installing things, such as using Yarn, NuGet, or Homebrew. However, consider the possibility that whoever is reading your README is a novice and would like more guidance. Listing specific steps helps remove ambiguity and gets people to using your project as quickly as possible. If it only runs in a specific context like a particular programming language version or operating system or has dependencies that have to be installed manually, also add a Requirements subsection.

