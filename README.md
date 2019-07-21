# Create-viirtualenv

How to create virtualenv                           
Install pip first                         
sudo apt-get install python3-pip                                        
Then install virtualenv using pip3                                
sudo pip3 install virtualenv 

Now create a virtual environment                                                 
virtualenv venv                                                     
you can use any name insted of venv                                                                

You can also use a Python interpreter of your choice                                     
virtualenv -p /usr/bin/python3.6 venv                                   

Active your virtual environment:                                               
source venv/bin/activate                                                    
                                                          

To deactivate:                                                                   
deactivate                                                     
 
Create virtualenv using Python3                                                                     
virtualenv -p python3 myenv                                                                       

Instead of using virtualenv you can use this command in Python3                                                   
python3 -m venv myenv                                                                   
  
