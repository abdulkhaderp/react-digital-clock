# react-digital-clock
A simple digital clock implementation in React.

# Installation
npm install react-digital-clock

## Usage
1. Import component : 

       import Clock from 'react-digital-clock';
2. Use component    :  

            <Clock />

Optional Props
            
 ####locale

 - Default: []  
 - Expected: true or false  
 - Function: To pass locale
 ##
                        <Clock runner={false} />
 
  ####runner
  
 - Default: true  
 - Expected: true or false  
 - Function: Flag to instruct whether clock need to run or display the static time when the component renders.
 - Example 
  ##     
                        <Clock runner={false} />
                        
 ####hour12
  
 - Default: true  
 - Expected: true or false  
 - Function: Flag to switch 12 Hour/ 24 Hour format.
 - Example 
  ##       
                        <Clock hour12={false} />                       
                        
  ####format
  
 - Default: 'hh-mm-ss'  
 - Expected: 'hh' / 'hh-mm' / 'hh-mm-ss'  
 - Function: To specify the display format of time.
 - Example 
  ##      
                        <Clock format={'hh-mm'} />                       
                              
 
 

