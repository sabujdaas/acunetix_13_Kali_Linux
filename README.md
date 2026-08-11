**acunetix-13 install in kali linux**
Acunetix is an end-to-end web security scanner that offers a 360 view of an organization's security.

**acunetix-13 Downloads Now:**  
      https://drive.google.com/drive/folders/1AVmy2OtMDl76VH79pLu3c-C_yzATbNDZ?usp=drive_link 

**open the downloads directory**  
      cd Downloads

**open the Acunetix_13 directory then**  
      cd Acunetix_13

**Need to file permutation**  
      chmod +x *

**Run command in terminal**  
      sudo bash ./acunetix_13.0.200217097_x64_.sh

**Run command in terminal**  
      sudo cp wvsc /home/acunetix/.acunetix/v_200217097/scanner/

**Run command in terminal**  
      sudo cp license_info.json /home/acunetix/.acunetix/data/license/

**acunetix status check**  
      service acunetix status 
      
**acunetix service run**  
       ```bash
       service acunetix start
      
**open the urls in the browser**  
      https://127.0.0.1:3443/
        or  
      https://kali:3443/

**acunetix stop**  
   ```bash
service acunetix stop 

