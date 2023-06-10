
---
Title:  Linux
Created: Thursday 8th June 2023 19:53
Topic: Linux
Aliases: 
Tags: 06-2023, Linux, linux, programming, commands
Type: Note
Author: Christian Flores 

---

#  [Linux]
Author: [[Christian Flores]]
[ ](#anki-card)
## 📝 Notes
- Linux security #permission
- ![[Pasted image 20230608195401.png]]
- type: - -> file, d -> directory.
- chmod: change security permissions
	- Example: add x permission to all users:
	```shell
	chmod o+x [file]
	```
	- u: user, g: group, o: others(all)
	 - Example: add all permissions to everyone
	```shell
	chmod ugo+rwx [file]
	```
- pipe(|) #pipe:  it "pipes" data from one command to another.
	```bash
	cat joke-1 joke-2 | lpr -P zephyr
	```
- grep: You can use "grep" to find patterns in data
	- Example: This would display every line of text in file "metals" that contained the pattern "gold".
	```bash
	grep gold metals
	```
- kill -9 PID: Kill immediately a process
- find: find a file
	```bash
	find ~ -name "poem*"
	```


#  [[Kernel]]
🏷️ Subject/Topics: #kernel #linux 
Date: 2023-06-09
Time: 18:06
- it allows the hardware to talk to the software.

## Questions/Thoughts
- What is ACLs?? Access control lists. link: https://linuxsurvival.com/linux-groups-command/
## 🔗 Links
- 