# Sort this out!!!
- in ths challenge we are given a text file and we have to check if it is sorted and if it is sroted we will print 1 else 0
- and when we run the code it will give binary string and when i convert it to ascii i get the flag
- https://github.com/Riduvarshinirs/Riduvarshini_CTFrecruitment23/blob/main/screenshots/a1d25790-d4e2-409d-9b2b-6f549f2b493c.jpg
- def is_sorted(line):
-   return line == ''.join(sorted(line))

- def lines_to_binary(input_file):
 -   output = ""
 -   with open(input_file, "r") as file:
 -       for line in file:
-            line = line.strip()  
-            if is_sorted(line):
-                output += "1"
-            else:
-                output += "0"
-    return output
-input_file = "data.txt"  
-binary_output = lines_to_binary(input_file)
-print(binary_output)
  
