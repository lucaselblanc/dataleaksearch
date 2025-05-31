# Data Leak Search - CyberSec Toolkit for android
Contains a small osint toolkit, includes data leak search and hash cracking.


- Has a hash cracking tool for the formats: MD5, SHA1, SHA256, MySQL4.1/5, NTLM, LM, RipeMD160, RipeMD256 and SHA224, uses dictionary/rules, brute force, dictionary + brute force with mask, dictionary + brute force without mask techniques and rainbow-table.

- Contains search for hashes in database leaks (online).

- User custom wordlist.

- Protect your privacy and prevent your personal data from being stolen with Data Leak Search.

- Data Leak Search performs reliable and secure searches for leaked information from companies and online services.

- Your personal data is valuable and deserves the best protection.

- With Data Leak Search, you will have easy access to the information you need to keep your data safe and prevent it from falling into the wrong hands. Stay secure right now, your protector against personal data leaks.

---

# Osint Search

### Data Leak Search: 
  BreachDirectory API

### Instagram Scraping: 
  Instagram API

---

# Hash Cracking Tool

### Test Device: 
  Redmi Note 9S | 6GB Ram | Octa-Core Max 2.32 GHz | Android 12

## H/s Benchmark:


*NTLM Hashes Per Second*: 355.000 *(Average)*

*MD5 Hashes Per Second*: 420.000 *(Average)*

*RipeMD160 Hashes Per Second*: 410.000 *(Average)*

*SHA1 Hashes Per Second*: 370.000 *(Average)*

*MySQL 4.1/5 Hashes Per Second*: 310.000 *(Average)*

*RipeMD256 Hashes Per Second*: 420.000 *(Average)*

*SHA224 Hashes Per Second*: 370.000 *(Average)*

*SHA256 Hashes Per Second*: 375.000 *(Average)*

*LM Hashes Per Second*: 105.000 *(Average)*

---

# Usage Information


  Attention, this tool uses brute force techniques using the Android CPU, brute force can be extremely time consuming depending on the complexity of the password and also the processor of your device, if you want to have superior cracking performance, I recommend using Hashcat for computer or Hash Suite Droid which uses the Android GPU instead of the CPU, this tool is in the testing phase, thank you!.

---

## CPU:


  In order to improve the efficiency of (Hashes Per Second) avoiding work overloads in Android OS scheduling and thread switching overhead, it was necessary to use only half of the available physical cores of the Android processor, this management is automatic according to the available cores on the processor:


Deca-Core: Of the 10 physical Cores, 5 will be used in threads.
Octa-Core: Of the 8 physical Cores, 4 will be used in threads.
Hexa-Core: Of the 6 physical Cores, 3 will be used in threads.
Quad-Core: Of the 4 physical Cores, 2 will be used in threads.
Dual-Core: Of the 2 physical Cores, 1 will be used in threads.
Single-Core: The only available core will be used in threads.

---

## Time estimate:


  Crack time estimation is inaccurate as there is a small margin of error that is impossible to avoid. Factors such as the position of the password within the search space, i.e. how early or late it appears in the possible combinations, affect the actual time needed to crack it, it is an unavoidable side effect, therefore the calculation takes into account all possible combinations: (N = m ^ n / hashesPerSecond--), this calculation is very simplified to facilitate understanding, but follows the same logic.

---

## Min Length vs Max Length:


  The min length must be less than or equal to the max length, the max length allowed is 64, but a password with more than 10 characters has many combinations, the calculation for the number of combinations is: (Value of combinations ^ password length), for example, for a password that only contains numbers from 0 to 9 and contains 4 digits, the calculation is: (10 ^ 4), the greater the value of combinations, the greater the exponentiation and consequently the longer the time required to crack.

---

## Hashes per second:


  Direct use of Android's CPU is less efficient in parallelization than using the GPU, so what is generally expected is approximately 400.000 hashes per second for md5 using an Octa-Core processor, there are 100 thousand hashes per virtual core, this tool is more efficient for short passwords.

---

Playstore Link: https://play.google.com/store/apps/details?id=com.NoClipStudio.DataBaseSearch
