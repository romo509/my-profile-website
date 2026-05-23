"Juan Romo enter Demonstration of deploying website to github pages. Attempt 2"

I needed to create a workflows directory with a yaml file under that directory.  My first attempt resulted in creating a file instead of a directly.  I had to add forward slash in front of workflows to create the directory.  I also had to investigate what path to use and had to change my page source form GitHub Actions to deploy from branch to get the correct path.
I am currently using node.js 20 and it will be depricated in September.  If I want this site to function after September, I need to change the runs: to node.js 24
