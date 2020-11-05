# AQUATONE

Install Aquatone from [here](https://github.com/michenriksen/aquatone).

## Usage

**Command-line options:**

![image](/images/Aquatone/1.png)

**Giving Aquatone data**

`$ cat targets.txt | aquatone`

**Specifying ports to scan**

`$ cat hosts.txt | aquatone -ports 80,443`

![image](/images/Aquatone/2.png)

### Output Format
When Aquatone is done processing the target hosts, it has created a bunch of files and folders in the current directory:

- **aquatone_report.html**: An HTML report to open in a browser that displays all the collected screenshots and response headers clustered by similarity.
- **aquatone_urls.txt**: This file contains all live URLs.
- **aquatone_session.json**: A file containing statistics and page data. Useful for automation.
- **headers/**: This folder contains response headers of targets domains.
- **html/**: This folder contains files of the response of target domains.
- **screenshots/**: This folder contains the screenshots of the target domains.

## Viewing Screenshots and data from html file in browser

![image](/images/Aquatone/3.png)

![image](/images/Aquatone/4.png)

![image](/images/Aquatone/5.png)

![image](/images/Aquatone/6.png)
