# Adventure-Resort-C-
# Adventure Resort - Activity Cost Calculator

This is a simple C++ console application that calculates the total cost for an adventure activity package based on the number of participants and the chosen package type.

## Features
- Choose from three adventure packages:
  - **Horse Riding**
  - **Scuba Diving**
  - **Water Rafting**
- Input the number of participants.
- Calculate the total cost based on the package and number of participants.

---

## Available Packages and Costs
| Package Type   | Cost per Person |
|----------------|-----------------|
| 1. Horse Riding | 2000 LKR        |
| 2. Scuba Diving | 5000 LKR        |
| 3. Water Rafting| 7000 LKR        |

---

## How to Use

1. **Compile the Program**:
   ```bash
   g++ -o adventure_resort adventure_resort.cpp
   ```

2. **Run the Program**:
   ```bash
   ./adventure_resort
   ```

3. **Follow the On-Screen Instructions**:
   - Select a package by entering the package type (1-3).
   - Enter the number of participants.

4. **View the Total Cost**:
   The program will calculate and display the total cost for the selected package and number of participants.

---

## Example Output
```plaintext
Adventure Resort
--------------------------------
Available Packages:
1.Horse riding
2.Scuba Diving
3.Water Rafting

Enter Package type (1-3): 2
Enter the Number of people: 3

The total cost for package type 2 for 3 people is 15000/=
```

---

## Notes
- The program will terminate with an error message if an invalid package type is entered.
- All costs are in LKR (Sri Lankan Rupees).

---

## Requirements
- C++ compiler (e.g., GCC)

---

## License
This project is open-source and free to use. Modify and share it as needed!
