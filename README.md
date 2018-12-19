
# Remove kaspersky password 

<h5> Here You can learn how to remove passwords of Kaspersky Products in Windows Platform</h5>

<h3>Step 1</h3>
    Press ' start+R ' to open ' Run ' and type msconfig 
    <img src="https://i.imgur.com/P70k8GN.png">
<h3>Step 2</h3>
    Make boot option to Safe boot Under boot Menu 
    <img src="https://i.imgur.com/IVLnQTg.png">
<h3>Step 3</h3>
    Restart your PC, it will boot up to safe mode
<h3>Step 4</h3>
     Press ' start+R ' to open ' Run ' and type regedit
     <img src="https://i.imgur.com/8rrPs5J.png">
<h3>Step 5</h3> 
     Goto  ' HKEY_LOCAL_MACHINE\SOFTWARE\KasperskyLab\AVP\settings ' if system is 32bit
     Goto  ' HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\KasperskyLab\AVP\settings ' if system is 64bit
     <img src="https://i.imgur.com/S3z6bhb.png">
<h3>Step 6</h3>
    Find ' Find enable password protection ' and make the value 1 to 0
    <img src="https://i.imgur.com/980csKb.png">
    <img src="https://i.imgur.com/5iL0Kt9.png">
<h3>Step 7</h3>
    Find ' OPEP ' and make it blank
    <img src="https://i.imgur.com/VNLcmsB.png">
    <img src="https://i.imgur.com/h8Tjtr1.png">
<h3>Step 8</h3>   
    That's all....
    Now you are successfully removed your Kaspersky product password....
    Change boot option to normal and restart your PC
    
    
