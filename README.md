# Keylogger
## Useful links:
[Keylogger Download](https://www.logixoft.com/index)

[Keylogger source code in Python](https://www.thepythoncode.com/article/write-a-keylogger-python)

[Example: Stealing Passwords From Windows Using a Remote Keylogger](https://www.youtube.com/watch?v=oM-kKk5RXeo)

## What is Keylogger?
Keylogger is a type of hacker software tool which could record keystrokes made by a user.[^1] Usually, the hacker implements the keyboard monitoring by using the Trojan program. The software keylogger is a computer program designed to record any input from the keyboard. Also, the keyloggers target the programs installed on a computer, smartphone, and electronic devices that require a password. 

Typically, a keylogger consists of three main parts: Control program: Used to monitor activity, adjust settings, and view the keylogger's log files. This part is the most hidden part of the keylogger and is usually only accessible via special shortcut key combinations. Hook files, or watchdog Log files for logging keystrokes, taking screenshots (this is the most important part), can log all stored/recorded hooks. Also, depending on the type, there may be additional guards (guard program), notifiers (report program). 

## How it does it
In systems, when a key on the keyboard is pressed, the keyboard converts it into a signal and transmits it to the CPU. The CPU passes it to the operating system for the operating system to translate into letters or numbers for use by itself or other programs. But when there is a keylogger in that system, not only the OS is monitored, but also the hook file/monitor that the keylogger monitors records and translates the signals written to the log file. It can also track screen and mouse movements.

![alt text](https://github.com/Fashion-Man/ECE-9609-9069-Introduction-to-Hacking/blob/main/Shows-how-Keyboard-works.png)[^2]

## How Keylogger is installed
Keylogger can be installed as software or hardware. If it is installed as software, it can be downloaded then installed, but it must stay hidden so that users do not alter the application. If it is installed as hardware, it must be an adapter between the keyboard plug and the computer port for the keyboard. It would be good to have a flagging technique if someone removes the device.

## Can keyloggers be detected?
Users are typically unaware that their keystrokes are being tracked since keyloggers are discretely installed along with a legitimate program and it's very difficult to know if there is a keylogger trojan installed on your computer. The easiest way to detect a keylogger is to use the help of security software and run a virus scan on your computer. Some ways to avoid the malicious attacks of keyloggers are to enable two-factor authentication, use a password manager, install antivirus software and avoid downloading unknown files.  

## How do keyloggers steal information?[^3]
### 1. API-based keyloggers
API based keyloggers register input from the keyboard as a normal part of an application instead of malware since these types of keyloggers allow for communication between software and hardware. Each instance a user presses and releases a key, the API-based keylogger records the information and exfiltrates the data. 

### 2. Form grabbing-based keyloggers
The second type of keyloggers is called form-grabbing based keylogger. These types of keyloggers extract information of users from forms that are submitted online. Once a user clicks a button or hits enter to submit the form, the keylogger will record all the data before the form is passed over the internet. 

### 3. Kernel-based keyloggers
Kernel-based keyloggers are the third category and they essentially have unrestricted access to data inputted into a user's computer system. The kernel-based keyloggers are able to do this by being installed into the system's core which gives them access at the admin level. 

### 4. Javascript-based keyloggers
The last type of keylogger we will cover here is the javascript based keylogger. Javascript-based keyloggers target websites to infect using malicious script tags. Once injected, the keylogger takes in keyboard input and extracts the data given by the user to the website. Different ways that a script is injected include man-in-the-middle attacks, cross-site scripting, or the keylogger can infect the website when the security of the website has been compromised. 

## The users
The hacker would want to use it to steal people’s password, or their private data. For example, when a user types in his online banking username and password, the hacker could copy that and transfer his money. However, the keylogger can help the clerk to record which websites have been visited and the applications (and some other activities) used by users of that computer. Also, parents can know what their kids are doing with the computer.

## Benefits with Keylogger
Keylogger can improve productivity by ensuring that employees that are on a computer stay focussed on their task. There would be a mental effect for people to stay concentrated on the task because one would not want someone with higher authority to know their deviation from the task. This is assuming that they know that a keylogger is installed.

Leading to not deviating from the task, would allow corporations to preserve bandwidth. Since network traffic for browsing is not free. If employees do not deviate from their task, there will be less waste of bandwidth, which should reduce bandwidth cost.

## Impact and significance
In general, Keylogger can improve productivity by making employees concentrate on the task at hand. Employee would have to know beforehand, and if there is true consequence, the employee would always obey the rule for not deviating from their work

## References
[^1]: https://en.wikipedia.org/wiki/Keystroke_logging
[^2]: https://www.researchgate.net/figure/Shows-how-Keyboard-works_fig1_309230926
[^3]: https://softwarelab.org/what-is-a-keylogger/
