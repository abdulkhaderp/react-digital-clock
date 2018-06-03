# react-digital-clock
A simple digital clock implementation in React.

# Installation
npm install react-digital-clock

# Usage
1. Import component : import Clock from 'react-digital-clock';
2. Use component    :  '<Clock />'
3. Done!

# Optional Props

1. locale - To pass the locale 
            #### Eg : <Clock locale={'ar-AE'} />

2. runner - Flag to instruct whether clock need to run or display the static time when the component renders.
            Default : true
            Eg: <Clock runner={false} />

3. hour12 - Flag to switch 12 Hour/ 24 Hour format.
            Default : true
            Eg : <Clock hour12={false} />
            
4. format - To specify the display format of time.
            Default : 'hh-mm-ss'
            Eg : <Clock format={'hh-mm'} />
            
  
