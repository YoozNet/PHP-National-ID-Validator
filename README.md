# PHP National ID Validator

This is a simple PHP script to validate Iranian national ID numbers based on the official checksum algorithm.

## Features
- Validates 10-digit Iranian national ID numbers.
- Performs checksum verification based on official rules.
- Returns a step-by-step breakdown of the validation process.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/YoozNet/PHP-National-ID-Validator.git
   ```
2. Navigate to the project directory:
   ```sh
   cd PHP-National-ID-Validator
   ```
3. Run the script in a PHP environment.

## Usage
```php
include 'validate.php';

$testID = '1234567890';
$result = validateNationalID($testID);
print_r($result);
```

### Example Output:
```
Array
(
    [input] => 1234567890
    [status] => Valid
    [steps] => Array
        (
            [0] => کد ملی معتبر است
        )
)
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author
Developed by **[YoozNet]**. Feel free to contribute or report issues!

## Contributions
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Contact
For any inquiries, you can reach me at [SaeedShanaqi+github@gmail.com] or open an issue in this repository.

