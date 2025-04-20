
## Consonant Counter Program  

**This C program counts how many consonant letters are in a sentence you type.**  

---

### 📝 Key Notes  
- **Won't crash if you type a lot, but the array is fixed only to 200.**  
- **Checks each letter from A-Z or a-z, and skips the vowel letters.**  
- **I find the `fgets` function easier to use when dealing with sentences.**  
- **The `scanf` gets too complicated at times when it comes to strings. I mostly use it for integers, 1-word strings, or characters.**  

---

### Why This Works  
- Uses `fgets()` for safe sentence input (avoids buffer overflow).  
- Loops through each character and checks against vowels (`A, E, I, O, U`).  
- Case-insensitive (handles both uppercase and lowercase). 
