# aws_cli_command_scrapping
Web scrapping description and code of AWS CLI from official documentation site.

Reference- https://docs.aws.amazon.com/cli/latest/reference/ec2/

<h2> Step1- </h2>

  
Extracting Names of all avilable commannds and their seperate hyperlink of further detailed documentation of individual command.

![Screenshot (1022)](https://user-images.githubusercontent.com/66110778/170886331-f21497ae-c6c4-4fa1-b652-27fd63c8ad94.png)

Output- Command name, link for seperate documentation page


<h2> Step2- </h2>

Looping over all the links. After getting the link of documentation for indivisual documentation extracted Aim, Command description and code example by selecting the appropriate html tag/class .


![Screenshot (1023)](https://user-images.githubusercontent.com/66110778/170886444-f7d59bf3-271a-4a37-a895-6aa7d6bf986b.png)

<h2> Output </h2>

For demo purpose extracted around 200 aws-ec2 commands and description

![image](https://user-images.githubusercontent.com/66110778/170886747-13ec3a4e-70c0-4f65-a3a7-655f7284974d.png)
