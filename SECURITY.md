# Security Policy


## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

## Reporting a Vulnerability

Use this section to tell people how to report a vulnerability.

Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
declined, etc.


***Uninstall useless modules that have vulnerabilities.  

If a version modules gives errors, change the "package-lock.json" to something else, such as package-lock1.json.  {in terminal within directory} To allow clean 'npm install -g npm'.
example (my system didn't like the deasync) I had to manually install with 'npm install deasync' after changing the lock json name.  
This created a new lock.json file which has various vulnerabilities after update.

Run 'npm audit' in terminal. Find git's on each and find solutions or google errors or vulnerabilities and if they matter to your build.
Run 'npm audit fix' or 'npm audit fix --force' to try to get those vulnerabilities to go away.


