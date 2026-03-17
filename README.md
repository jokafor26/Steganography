# Steganography

Image Files & Steganography Tools


In this project I use S-Tools4 to create a steganography file to hide information within an image. 
I created my own Findme.txt file to include into an image.
 <img width="534" height="138" alt="image" src="https://github.com/user-attachments/assets/bd4b4fa3-abad-470f-87bb-2e9bff1bea1f" />


I loaded an image into S-Tool then dragged the findme.txt file into the image. In the Hiding dialog box, I typed freedom in the passphrase and verify passphrase text box and clicked ok. 
  <img width="715" height="423" alt="image" src="https://github.com/user-attachments/assets/a37311c5-81aa-407d-8f8a-447e132ebf3c" />
<img width="541" height="202" alt="image" src="https://github.com/user-attachments/assets/47686b0a-5ff0-4023-a7fd-8db4b43cfc69" />


A Steg.bmp image file would be created with minor differences. Which is that they have roughly are the same size. The steg picture that was created had 799kb while the original had 789kb and doesn’t have the text file in it.   
 
<img width="658" height="580" alt="image" src="https://github.com/user-attachments/assets/12803c7e-c035-424f-947c-15c7b81dada0" />

I would use S-Tool4 to create a secret message in a bitmap file and compare the stg file with my original file by using the DOS comp command. I would drag the mission.bmp file from my folder into the s-tool window and then insert the rtf file into as well. Hop08-5 is the passphrase and verify passphrase.
 
 <img width="573" height="214" alt="image" src="https://github.com/user-attachments/assets/455c53da-6248-450b-9a1b-51bef8d5424e" />

<img width="679" height="435" alt="image" src="https://github.com/user-attachments/assets/02d81648-df86-4a1e-8259-27c109e6efbe" />

I would then open a terminal and change into the folder by using the cd command. once in I used the command comp mission.bmp mission-steg.bmp which would compare the original image file and the steg created file. Saw minor differences in the letters after the initial first letter. There are 10 mismatches located.
 <img width="741" height="501" alt="image" src="https://github.com/user-attachments/assets/002f90af-bbdf-4688-b0c2-56aef99567f5" />


Using the s-tool I revealed the hidden message in the fox2.bmp image with the passphrase as cst3520 using Triple DES as the encryption algorithm.
 <img width="211" height="184" alt="image" src="https://github.com/user-attachments/assets/df5b596e-6c19-421a-abc7-4eca65aadd16" />
<img width="541" height="202" alt="image" src="https://github.com/user-attachments/assets/3d2c142f-d4c2-40a1-a631-3fb50ca4cf2a" />

 

After inputting the passphrase another image appears labeled hidden data and shows the archive which displays that the hidden message is the findme.txt
 <img width="576" height="373" alt="image" src="https://github.com/user-attachments/assets/ab6b244f-f32d-4312-8d62-a611d5c61d6c" />


Here I tried to utilize the WinHex to fix the header of a file called moon2.tif. I used the link https://en.wikipedia.org/wiki/List_of_file_signatures to find out the good sample header.
 
<img width="623" height="738" alt="image" src="https://github.com/user-attachments/assets/1c336c45-15b8-4c08-a3b3-ae4370ff70d9" />
