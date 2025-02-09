# Update a File Through a Python Algorithm

## Project Overview  
I worked on this project to practice managing an allow list for restricted content using Python. Through this, I learned how to automate the process of updating the allow_list.txt file by removing IP addresses found in a separate remove list. This helped me understand file handling, list manipulation, and how automation can improve security management.  

## Technologies Used  
- **Python** (for automation)  
- **File Handling** (reading, modifying, and updating text files)  
- **List & String Manipulation** (for efficient data processing)  

## Features  
- Open and read an allow list of IP addresses  
- Convert file content from a string to a list for easier processing  
- Iterate through a remove list and delete unauthorized IPs  
- Write the updated allow list back to the file  

## How It Works  
1. **Read the allow list**: I open `allow_list.txt` and store its contents.  
2. **Convert to a list**: I split the string into a list of IPs for easier manipulation.  
3. **Remove unauthorized IPs**: I check and remove any IP found in the remove list.  
4. **Update the file**: I convert the list back into a string and write the revised allow list back to `allow_list.txt`.  
