# Honeypot Assignment

**Time spent:** **4** hours spent in total

**Objective:** Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

### MHN-Admin Deployment (Required)

**Summary:** I used Google Cloud in order to deploy all my virtual machines for this assignment. It's ease of use was great and interaction with the CLI helped me get a better undertanding of the Google Cloud deployment landscape.

![Kapture 2022-11-11 at 21 48 56](https://user-images.githubusercontent.com/70921921/201453193-53d0eff3-3075-4d5f-880d-14158a8dace5.gif)

### Dionaea Honeypot Deployment (Required)

![image](https://user-images.githubusercontent.com/70921921/201459714-868cf69b-e309-41da-abb6-2ea519e8b14b.png)

**Summary:** In simple terms, Dionaea is a tool that traps malware exploiting vulnerabilities and exposed services going towards a network. Security professionals use a tool such as this in order to gain a copy of the malware and perhaps do sandbox analysis of said malware, but in our case we used it to catch port sniffers.

![Kapture 2022-11-11 at 21 55 08](https://user-images.githubusercontent.com/70921921/201453331-939c5285-5936-42f3-9ae9-20b76a4d7425.gif)

### Database Backup (Required) 

**Summary:** I believe MHN-Admin uses MongoDB to store data. The information stored within the JSON file is data on attacks to our deployed page, with IP information, source and destination ports, timestamps, protocols and what looks to be potential methods that attackers/scanners have used as I see names such as Black Hole and pcap that I'm not too familiar with.

*JSON file uploaded to GitHub.*

## Notes

My main challenges with this assignment involved setting up Google Cloud. Once I got the service up and running and set up an account, I had to look at a lot of documentation in order to troubleshoot some issues I was having, but after some perseverance I coasted through the rest of the setup process and was able to complete the assignment easily. It goes to show how people learning this field need to be prepared when it comes to understanding online documentation of tools that you may not have worked with before, and thus this helped me in a sense that I'm not very familiar at all with the Google Cloud platform and using it to deploy these VMs both showed me how powerful it can be and  a basic run down on how to set it up.
