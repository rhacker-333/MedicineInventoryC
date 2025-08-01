# MedicineInventoryC

## Description
MedInventoryManager is a simple Medical Inventory Management System written in C. It provides a command-line interface to add, display, search, update, and delete medicine records stored in a binary file. This project demonstrates fundamental concepts of file handling, structures, and CRUD operations in C.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c72de0fe-c4fc-471d-8ad9-5bec15f4f76d" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/49b30891-7465-410d-8e89-57a6d0916a39" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d4ba2850-6807-47b8-805d-e1e9ac14c6b8" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/97f4b293-0752-45f6-a53f-293961de9662" />


## Features
- Add new medicine records with name, quantity, and price.
- Display all stored medicine records.
- Search for a particular medicine by name.
- Update the quantity and price of existing medicines.
- Delete medicine records.
- File-based storage using binary files for persistence.

## Getting Started

### Prerequisites
- A C compiler (e.g., GCC via MinGW on Windows, or GCC on Linux/macOS).
- Command-line interface (Command Prompt, Terminal).

### Compilation and Running
1. Clone or download the repository.
2. Open the command line and navigate to the project directory.
3. Compile the program using:

gcc medical_system.c -o medical_system.exe


4. Run the executable:


## Usage
Follow the on-screen menu to perform operations:
- Enter numbers (1-6) to choose options like viewing, adding, searching, updating, deleting medicines, or exiting.
- Input required data when prompted.

## File Handling
All medicine records are saved in `medicine.dat` in binary format within the project directory. The system automatically updates this file on modifications.

## Contributing
Contributions are welcome. Please fork the repository and submit a pull request.

## License
This project is open source and available under the MIT License.

---

*Created on Wednesday, July 23, 2025*



