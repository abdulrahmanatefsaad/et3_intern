
## Word Frequency Analyzer

### Description
A program that analyzes a `.txt` file and reports word frequencies, ignoring punctuation and case, and displaying the top 10 most frequent words.


### Java Implementation (`WordFrequencyAnalyzer.java`)

**How to Run:**

1. Ensure you have Java Development Kit (JDK) 8 or higher and Maven installed.
2. Navigate to the root directory of the project (where `pom.xml` is located).
3. Compile and package the application using Maven: `mvn clean compile assembly:single`
4. Run the application 

**Commands:**

- `<file_path>`: The path to the text file to analyze. 

## Extra Features and Notes
- Ignores punctuation and case for accurate word counting.
- BufferedReader: It reads the file line by line, not all at once, so memory usage stays low even for huge files.
- Streaming Processing: Regex matching happens per line instead of scanning the entire file as one string.
- HashMap: provides O(1) average-time insert/lookup for counting words.
- Error Handling:** Basic error handling is included (e.g., file not found, invalid input).

**Bonus Features:**
- Generate a simple bar chart of the top words.
- Handle large files efficiently.




