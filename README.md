![Screenshot 2025-03-20 112209](https://github.com/user-attachments/assets/beebb1cc-34ed-4a83-ad2a-5e8cca0819d0)# Experiment-1
##  Write programs in Python Language to demonstrate the working of
followingconstructs with possible test cases: a) do…while b) while…do c)
if …else d) switch e) for

## a) Aim
To write python programs for do…while, while, for, switch and if…else and test with possible test
cases.

## Algorithm
1.	Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4. Test the program with possible test cases.
5. Stop the program. 

## Programs:

## a) do…while
~~~
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")

    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)

        while True:
            print(start, end=' ')  # Corrected quote

            if start < end:
                start += 1
            else:
                break
    else:
        print("Enter a valid positive number.")

display()
~~~

## Output
![Screenshot 2025-03-20 112209](https://github.com/user-attachments/assets/44bfb87e-a0e6-477f-9ac8-30deb173f73e)
![Screenshot 2025-03-20 112220](https://github.com/user-attachments/assets/57a0e702-f03c-4daf-b02e-65c3812638cf)
![Screenshot 2025-03-20 112230](https://github.com/user-attachments/assets/88fcf9c5-924d-410f-9f11-f2e5555ab8f8)
![Screenshot 2025-03-20 112301](https://github.com/user-attachments/assets/2e1b855e-ca61-4d0c-aa1f-53329aca22dd)

## Result




