# To find a process on Specific port <br>
  netstat -aon | findstr '[port_number]'  <br>
  e.g. netstat -aon | findstr 8080        <br>
  
# To kill the process            <br>
  taskkill /F /PID taskId     <br>
  e.g. taskkill /F /PID 3312    <br>
