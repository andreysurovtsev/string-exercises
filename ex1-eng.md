## C String Exercises (`<string.h>`)

### Setup (common to all exercises)
```cpp
const int N = 1000;
char s[N];
cin.getline(s, N);
```

---

## 🟢 Level 1 — Very Easy (warm-up)

### 1️⃣ Count the number of characters (excluding `'\0'`)
**Task:** Count how many characters the string contains.

**Focus:**  
- `strlen`

---

### 2️⃣ Remove all spaces from the string
**Task:** Modify the string so that all `' '` characters are removed.

**Example:**  
Input: `"hello world test"`  
Output: `"helloworldtest"`

**Focus:**  
- `strlen`
- manual shifting / rebuilding

---

### 3️⃣ Count how many times a given character appears
**Task:** Read a character `c` and count how many times it appears in the string.

**Focus:**  
- `strlen`
- basic traversal

---

## 🟡 Level 2 — Easy / Medium

### 4️⃣ Count the number of words
**Task:** Count how many words are in the string (words separated by spaces).

**Focus:**  
- `strtok`
- token counting

---

### 5️⃣ Count how many words are longer than `x`
**Task:** Read an integer `x`. Count how many words have length strictly greater than `x`.

**Focus:**  
- `strtok`
- `strlen`

---

### 6️⃣ Find the longest word
**Task:** Find and display the longest word in the string.  
If there are multiple, display the first one.

**Focus:**  
- `strtok`
- `strlen`
- keeping a “best so far”

---

## 🟠 Level 3 — Medium

### 7️⃣ Find the word that is lexicographically maximum
**Task:** Find the word that is **largest in lexicographical order**.

**Example:**  
`"apple banana pear"` → `"pear"`

**Focus:**  
- `strtok`
- `strcmp`

---

### 8️⃣ Replace all occurrences of a word with another word
**Task:**  
Read two words: `oldWord` and `newWord`.  
Replace **all occurrences** of `oldWord` with `newWord`.

**Focus:**  
- `strtok`
- `strcmp`
- `strcpy`, `strcat`
- building a new result string

---

## 🔵 Level 4 — Medium / Tricky (but still reasonable)

### 9️⃣ Check if the string is a palindrome (ignoring spaces)
**Task:** Determine if the string is a palindrome, ignoring spaces.

**Example:**  
`"nurses run"` → palindrome

**Focus:**  
- `strlen`
- character comparison
- preprocessing (removing spaces)

---

### 🔟 Count how many distinct words appear in the string
**Task:** Count how many **distinct** words appear.

**Example:**  
`"ana are ana mere"` → `3`

**Focus:**  
- `strtok`
- `strcmp`
- storing words in a 2D `char` array

---

## 🔑 `string.h` functions covered
- `strlen`
- `strtok`
- `strcmp`
- `strcpy`
- `strcat`
