---
title: Join
excerpt: "Joining KAIST Concurrency and Parallelism Laboratory"
---

- If you're interested in joining the [Concurrency and Parallelism Laboratory]({{ site.baseurl }}) as a graduate or undergraduate student,
  please **CONTACT Jeehoon (`jeehoon.kang@kaist.ac.kr`) NOW**.  Don't wait for some events to happen.  Again, contact NOW.
  Otherwise, the opportunity may go to the other students.

- When you contact Jeehoon, he will ask you to introduce yourself.
  The introduction should at least contain:

    + The most interesting experience (computing wise) you've experienced in the past.
      It can be about course projects, research or industry experience, or anything related to computing.
      Please prepare for a [Google Docs](https://docs.google.com) document that clearly describes the experience,
      and give the document's comment access to `jeehoon.kang@cp.kaist.ac.kr`.

    + What you want to do in the lab.
      Please read this website's [research page]({{ site.baseurl }}{% link index.md %}#research) and [recruit page](https://www.facebook.com/groups/kaistcomputerscience/permalink/2970178453084074){:target="_blank"};
      study what's going on in this lab;
      write down your plan as a Google Docs document;
      and give the document's comment access to `jeehoon.kang@cp.kaist.ac.kr`.

    + When you and Jeehoon can meet for 30 minutes online.
      Please look at [Jeehoon's calendar]({{ site.baseurl }}/jeehoon.kang#calendar) for his schedule.

- After sending an email to Jeehoon, please carefully read the entirety of this document.
  You also need to do all the action items, e.g., watching Derek's talks (see below) or learning development tools.
  Make sure you finish doing so before joining this lab. Please let Jeehoon know about your progress.

- If your email does not contain the above information, Jeehoon will reply to you with the following message:

  > 안녕하세요, 강지훈입니다.<br /><br />
  > 연구실에 관심 가져주셔서 감사합니다.<br />
  > 다음을 읽어주세요: https://cp.kaist.ac.kr/join<br /><br />
  > 감사합니다.<br />
  > 강지훈 드림

- Jeehoon will leave a few comments to your documents.
  Please address them or give counterarguments against them.

- I require all new graduate students to finish at least one of the followings before joining the lab:

    + Homework assignments of [KAIST CS420: Compiler Design](https://github.com/kaist-cp/cs420).
      Lecture videos are uploaded to YouTube, and you can ask questions in the course repository's issue tracker.

    + Homework assignments of [KAIST CS492: Concurrent Programming](https://github.com/kaist-cp/cs492-concur).
      Lecture videos are uploaded to YouTube, and you can ask questions in the course repository's issue tracker.

    + [Software Foundations](https://softwarefoundations.cis.upenn.edu/) Volumes 1 and 2.
      You can ask questions in this repository's issue tracker.

  So if you're interested in joining this lab as a graduate student, please start working on one of
  them.

  Also, I recommend new undergraduate student interns to work on one of them, too.


## Onboarding

Welcome to the lab! Please read this document as the first task in this lab.

### What is Research?

> "Research is what I am doing when I don't know what I am doing," Wernher von Braun

The defining characteristic of research is everything---from motivation to methods to evaluation to
goal---is tentative: in the middle of doing research, you don't know what will be the end result. As
a consequence, a researcher will suffer everyday from:

- **Failures**. You don't know what you're doing, so you'll fail almost always. To deal with
  the frustration from such failures, you should be mentally tough enough to tolerate such
  frustration. If successful, from time to time you will be able to understand or design small
  things, which accumulate to a paper and a thesis.

- **Changing plans**. You don't know what you're doing, so your goal will be changing as you make
  progress on your project. So any long-term plan is destined to be significantly revised. Thus you
  should think of the goal as a ever-moving target, the current version being just the best possible
  approximation of the actual end result. Your goal should be neither too concrete nor too abstract:
  if too concrete, it will not be resilient to the revision; if too abstract, it will not guide your
  research.



### Management Principles

To get things done despite the fundamental uncertainty of research, this lab (ironically) aims to keep tangential uncertainty to the minimum.
All uncertainty are not created equal.
Some uncertainty, such as confusion on schedule or communication, is not beneficial for productivity.
On the other hand, other uncertainty, such as unexplored design spaces, is the very definition of research.
To be productive, we need to keep the former to the minimum and control the latter to the appropriate amount.
(The meaning of "the appropriate amount" constitutes a researcher's character; at first, please follow Jeehoon's taste.)

To minimize the unnecessary uncertainty, this lab enforces a small number of rules on communication.
Rules are good at minimizing confusions.
For example, is it okay to mention someone in chatting applications during night time?
People have vastly different opinion on this, possibly causing unnecessary tension among them, so we want to *define* whether it's acceptable or rude in a rule.
(FYI, we allow night-time mentions, but you're required to react to them only in work hours.)
On the other hand, rules are hard to follow if there are so many.
So we want to keep the number of rules as low as possible.



### Communication

#### Mode of communication

- **Always, strongly prefer asynchronous communication**: the receiver is not required to reply promptly.
  If you can say something asynchronously, please do it so as early as possible.
  For example, you want Jeehoon to review your document, please send it to him as soon as you finish writing it. Don't wait for the meeting time to come.
  Please address Jeehoon's comments as soon as possible, and when it's done, please notify him of the progress.

- Even for asynchronous communication, try to reply within 12 hours.

- Before asking for a synchronous meeting (face-to-face or online), write down a meeting agenda and share it.
  In the agenda, clearly state the purpose of meeting. It can be, but not limited to: (1) reporting the progress, (2) asking questions/opinions, or (3) just chatting.
  If you have multiple things to discuss, enumerate them at the beginning of a meeting for better planning of the meetings.

    + If you don't send an agenda, the meeting is potentially going to be canceled.
    + **If the meeting is to discuss a document, please send it at least by 12 hours before the meeting** so that the others can review it.
      Share it anyway even if you couldn't finish writing the document by the time, because the others need to start making comments on it.


#### Volume of communication

- **At 10am and 3pm everyday, please leave about five sentences to the [daily log](https://cp-chat.kaist.ac.kr/#narrow/stream/16-daily-log)** about what you'll do and what you've done for the day.

- Schedule at least one meeting for at least 15 minutes a week with Jeehoon.
  It can be about anything such as research, coursework, TA...

#### Reliability of communication

- **Make sure that no feedbacks or action items get ignored.**
  More concretely, when you receive a feedback, address it or give a counterargument against it.
  When you're not capable of doing action items by their deadline, please say so as early as possible.

    + If you're reliable on this, the others can depend on you to get things done.
      If you're unreliable and you miss feedbacks or action items, the others also need to track them, which causes great management cost.

- **Right after every meeting, write down and share action items** in the corresponding Zulip topics (Team stream or DM).
  Example:

        * pr #131 적정 단계에서 끊어서 마무리하겠습니다.
        * XX에 대해 정리하여 공유하겠습니다.
        * issue #124 검토하겠습니다.

- Don't say yes (or no) if you're not sure about this.
  Don't say you understood something if you don't.
  If there are some points that you do not understand clearly during the discussion, ask as soon as possible.

- Don't be angry or grumpy when the discussion is getting hotter.
  *Hot discussion* is absolutely necessary for research and any other creative works, but it's hot because different opinions are clashing.
  It should not be hot because different emotions are clashing.

- Cleary distinguish what you cannot agree on and what is not important.
  Even if you don't agree with an argument, please faithfully treat and document it (esp. that you don't agree with it).

#### Writing and speaking skills for communication

- **Try to be direct, top-to-bottom, and conclusion-first** (e.g., not "A, so B, so C", but "C, because B, because A").

- **Read how to write papers and give talks by [Dr. Derek Dreyer](https://people.mpi-sws.org/~dreyer/)**:
    + [How to write papers so people can read them](https://people.mpi-sws.org/~dreyer/talks/talk-plmw16.pdf), PLMW@POPL 2016
    + [How to give talks that people can follow](https://people.mpi-sws.org/~dreyer/talks/talk-plmw18popl.pdf), PLMW@POPL 2018
    + [How to write papers and give talks that people can follow](https://people.mpi-sws.org/~dreyer/talks/talk-plmw17icfp.pdf), PLMW@ICFP 2017

- When you summarize an existing paper or write a proposal for a new paper, organize your document using Derek's CGI model.
  An example: https://docs.google.com/document/d/1W8coma11JFp0JIaVqFnZYkEa0sBkgZ1ijTSh6j8c_Gw


#### Tools for communication

##### Registration

When you first come to the lab, please do the following instructions:

- Create {firstname}.{lastname}@kaist.ac.kr email account.
    + You can add "additional account" in mail.kaist.ac.kr > Settings > My Account > Additional account.
    + If it is already taken, add a number at the end of the id, e.g., {firstname}.{lastname}07@kaist.ac.kr
- Send your email address and GitHub ID to jeehoon.kang@kaist.ac.kr.
- Your GitHub ID will be invited to `kaist-cp` organization.
- You'll get {firstname}.{lastname}@cp.kaist.ac.kr Google Workspace account.
- You'll get a [Zulip](https://cp-chat.kaist.ac.kr) account. Log in with your Google Workspace account.
- Make sure you finish read the entirety of this document and did all the action items, and DM Jeehoon in Zulip that you did so.

##### Zulip

- Instant messaging service at https://cp-chat.kaist.ac.kr.

- Zulip is also asynchronous by default, but it is semi-synchronous in work hours.
  Try to reply promptly (at most by 15 minutes) in work hours. (No need to even reply in other times.)

##### Email

- Use `{firstname}.{lastname}@kaist.ac.kr` email account for all work emails (not `@cp.kaist.ac.kr`).
- Forward all `{firstname}.{lastname}@kaist.ac.kr` emails to `{firstname}.{lastname}@cp.kaist.ac.kr` and check emails in [Gmail](https://www.gmail.com).
- Configure the Gmail account to send from `{firstname}.{lastname}@kaist.ac.kr`.
    + Go to https://mail.kaist.ac.kr > Settings - enable **SMTP**.
    + Go to [Gmail](https://www.gmail.com) > Settings > Click **See all settings** > **Accounts** > Click **Add another email address** > Add `{firstname}.{lastname}@kaist.ac.kr` and set it as the default address > Set **Always reply from default address**

- Write [proper formal emails](https://www.wikihow.com/Write-a-Formal-Email). Do not markup emails.

##### Calendar

- Use `{firstname}.{lastname}@cp.kaist.ac.kr` account for calendar and other Google Workspace applications.
- If you want to have a meeting, just directly invite the others in [Google Calendar](https://calendar.google.com). In the invitation, write the meeting agenda as described above.

##### Google Drive, Docs, Spreadsheet, slide

- Put all project-related files to Google Drive.
- Write docs/spreadsheet documents and make slides using Google's tools.

##### GitHub

- All work should be done in the [`kaist-cp` organization](https://github.com/kaist-cp).
- Please write your name in your public profile (Settings > Profile > Name).
- If you want to create a new repository, ask Jeehoon.
- Configure notifications for mentions and issue/PR comments.
  It is usually configured in Zulip, but if not, please get email notification for them.

##### Website

Create and maintain your website at `https://cp.kaist.ac.kr/{firstname}.{lastname}`.

- Fork [the website repository](https://github.com/kaist-cp/kaist-cp.github.io) and clone it.
- Install dependent libraries and run a local server to test by following commands:
      ```bash
      # Make sure Ruby is installed.
      $ bundle install
      $ bundle exec jekyll serve
      ```
- Add your meta information(name, status, github ID, etc.) to `people.yml`.
- Make a new file `{firstname}.{lastname}.md` under the directory `_people/`.
- Write your concrete information on the `{firstname}.{lastname}.md`. I recommend you refer to `_people/jeehoon.kang.md`.
- Make a commit, push it and PR.



### Development Tools

Before joining the lab, you should become familiar with a few development tools.

- Learn Vim, Emacs, or VSCode. (FYI, the winner of the editor war: vim vs emacs is vs(code).)
- Learn Git. FYI, [this tutorial](https://www.atlassian.com/git/tutorials) is a good introduction.
- Learn the other development tools introduced in [this course](https://missing.csail.mit.edu/) ([Korean translation](https://missing-semester-kr.github.io/)), except for "Editors (Vim)".


### Equipment and Tutorials

- Use the following devices (**IMPORTANT: no password should be written here. It's a public repository.**):

    + WiFi: `kaist-cp` at Rm. 4441, Bldg. E3-1, KAIST

    + Printer: `HP Color LaserJet Pro MFP M479fdw`; `10.12.255.2` in the WiFi network; AirPrint protocol

        * Scanning to a network folder on Ubuntu
            1. Make sure that your computer is in the lab local network.
            1. Creating a local network shared folder
                1. Create an empty directory.
                1. On nautilus, right-click and select Local Network Share. This will ask you to install a package called "samba" or something. Install it.
                1. Enter "Share name" e.g. `scan`.
                1. Check both "Allow others to create ..." and "Guest access ...".
                1. Run these commands:
                    ```
                    sudo ufw allow samba
                    sudo smbpasswd -a $USERNAME
                    ```
                1. Run this to check if it's configured correctly:
                    ```
                    YOUR_LOCAL_IP_ADDRESS=$(hostname -I | awk '{print $1}')
                    nautilus smb://$YOUR_LOCAL_IP_ADDRESS/scan
                    ```
            1. Configuring the scanner
                1. Enter the printer's IP address in the web browser.
                1. Scan > Scan to Network Folder > Quick Sets > +
                1. Fill in the form and click "Next".
                1. Set "Network Path" to `\\$YOUR_LOCAL_IP_ADDRESS\scan`, check "Use credentials of the user ...", then click "Apply"
            1. In the printer's control panel: Scan > Network folder > select the configuration you made in the previous step.

    + Server (Ubuntu): `ssh -p<port> <google-workspace-id>@cp-service.kaist.ac.kr` (e.g., `ssh -p11001 jeehoon.kang@cp-service.kaist.ac.kr`)

        * port: 11001, 11009, password: \<google-workspace-password\>

        * `/kaist-cp-home/<google-workspace-id>` is the home directory, but it's network-mounted.
          Run `sudo kaist-cp-refresh.sh`, then you'll have `/local-home/<google-workspace-id>` in the local SSD.

        * If you want to install additional packages, make a PR to [this
          repository](https://github.com/kaist-cp/infra-public/tree/master/sandbox-20.04), and after the
          PR is merged, run `sudo kaist-cp-refresh.sh`.
          
        * Configure SSH in your local machine properly.
          See <https://www.ssh.com/academy/ssh/keygen>, <https://www.ssh.com/academy/ssh/copy-id>, <https://linuxize.com/post/using-the-ssh-config-file/>. 
          Create ed25519 keys.

    + Remote desktop (Xubuntu): `cp-service.kaist.ac.kr:12001`

        * Protocol: RDP (security: TLSv1.2, TLSv1.3)

        * Client: [Microsoft clients](https://docs.microsoft.com/en-us/windows-server/remote/remote-desktop-services/clients/remote-desktop-clients), [Remmina](https://remmina.org/)

        * Credential: google workspace id/password

        * (SSH: `ssh -p14001 <google-workspace-id>@cp-service.kaist.ac.kr`)

    + Desktop: We encourage you to install the latest Ubuntu.

        * Configuring Hangul input method

            * Using Ibus (Ubuntu default) (**NOT recommended**. Use nimf instead.)
                1. Alt+F1 and search "Region & Language" > Input Sources > + > Korean > Korean (Hangul)
                1. Alt+F1 and search "Region & Language" > Input Sources > English (US) > Remove
                1. You can switch between Korean/English input method by pressing shift+space.

            * Using [nimf](https://github.com/hamonikr/nimf/)
                1. In "Region & Language" > Input Sources, remove other input sources and leave English (US) only.
                1. To check if nimf is installed, run `nimf-settings`. If it's not installed, run `/usr/bin/install-packages`.
                1. Run `im-config -n nimf` and reboot. Ensure that `nimf` process is running.
                1. Configure nimf with `nimf-settings`.
                   In "XKB options > Korean Hangul/Hanja keys", set "Make right Alt a Hangul key".
                   In "Nimf > Hotkeys for rotating input method engines", add "Hangul".

    + (If needed) Lab VPN

        * You can access the network inside the lab by running `ssh -p11000 <google-workspace-id>@cp-lab.kaist.ac.kr` (e.g., `ssh -p11000 jeehoon.kang@cp-lab.kaist.ac.kr`)
        * You can jump right into lab resources using `-J` ([`ProxyJump`](https://www.redhat.com/sysadmin/ssh-proxy-bastion-proxyjump)) option. (e.g.,  `ssh -J jeehoon.kang@cp-lab.kaist.ac.kr:11000 user@target-internal-ip` )
        * Since editors are not installed on the VPN instance, use `scp` to edit `.ssh/authorized_keys`. (e.g., `scp -P11000 ~/.ssh/authorized_keys jeehoon.kang@cp-lab.kaist.ac.kr:~/.ssh`)
