#include <iostream>
#include <string>

int main() {
    // Declare variables
    std::string firstName, lastName, streetAddress, city, zipCode;

    // Get user input
    std::cout << "Enter First Name: ";
    std::getline(std::cin, firstName);

    std::cout << "Enter Last Name: ";
    std::getline(std::cin, lastName);

    std::cout << "Enter Street Address: ";
    std::getline(std::cin, streetAddress);

    std::cout << "Enter City: ";
    std::getline(std::cin, city);

    std::cout << "Enter Zip Code: ";
    std::getline(std::cin, zipCode);

    // Print the information with improved formatting
    std::cout << "\nFictional Person Information:\n"
              << "-----------------------------\n"
              << "First Name:    " << firstName << "\n"
              << "Last Name:     " << lastName << "\n"
              << "Street Address:" << streetAddress << "\n"
              << "City:          " << city << "\n"
              << "Zip Code:      " << zipCode << "\n";

    return 0;
}
