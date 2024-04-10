# Ramiz Hajj
![Profile Picture](path/to/profile_picture.png)

## About Me
Hi, I'm Ramiz! I'm a programmer and student. Feel Free to contact me!
   > Jump to [Contact](###Contact)

## Background
I am a fourth year math and computer science maor, pursuing a career in software engineering. I am currently in a computational biology lab at the **Salk Institute** under **Dr. Talmo Pereira**. I will also be interning at **Northrop Grumman** this summer as a software engineer.
Here is a link to the lab I am in. **External link**:
   > Visit [Salk](https://talmolab.org/) for more information about SLEAP and computational biology research.

### Interests
- _Web development_
- _Machine learning_
- _Open source contributions_
- _Computational biology_
- _Cloud engineering_

### Quoting text
**A Motivational Quote**:
   > "The future belongs to those who believe in the beauty of their dreams." - Eleanor Roosevelt
### Quoting Code
**I wrote a function to parse a file's name and convert it into a more readable format**:
   > ```
   >import java.io.*;
        import java.util.Scanner;

        public class App {

        //read files
        public static String[] parseLineBySpaces(String line) {
            return line.split("\\s+");
        }
        public static void main (String[] args) throws Exception {
            System.out.println(System.getProperty("user.dir"));
            //Creating the File object
            File file = new File("ramiz/dnsmasq/src/ASUSDDWRT-dnsmasq.leases");
            //Creating a Scanner object
            Scanner sc = new Scanner(file);
            //StringBuffer to store the contents
            StringBuffer sb = new StringBuffer();
            //Appending each line to the buffer
            while(sc.hasNext()) {
                //output files
                String[] parts = parseLineBySpaces(sc.nextLine());
                for (String part : parts) {
                    String ipAddress = parts[2];
                    String deviceName = parts[3];
                    String newFormat = String.format("<a class=\"btn btn-primary\" href=\"https://%s:4200/\" target=\"_blank\">%s</a><br><br>", ipAddress, deviceName);

                    System.out.println(newFormat);
                }
            
   > ```

**Screenshots for lab **:
   > View [screenshots](screenshots.md) for necessary screenshots for the lab.


**Task list**:
   - [x] Create User Page
   - [ ] Add projects to User Page
   - [ ] Update About Me section

### Contact
You can reach me via email at [rhajj@ucsd.edu] or connect with me on [LinkedIn](linkedin.com/ramizhajj).
