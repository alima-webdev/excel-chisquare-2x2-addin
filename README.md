# Excel Chi-Square 2x2 Add-in

This Excel add-in provides two convenient functions to calculate the p-value for a 2x2 chi-square test directly within your spreadsheet. Whether you need a straightforward chi-square test or one that includes Yates’ correction for continuity, this add-in has you covered.

## Functions
### CHISQ2X2(a, b, c, d)
Calculates the p-value for a 2x2 chi-square test.
- Parameters:
	- a: The count in cell A1.
	- b: The count in cell A2.
	- c: The count in cell B1.
	- d: The count in cell B2.

Example:
```
=CHISQ2X2(10, 20, 30, 40)
```

### CHISQ2X2YATES(a, b, c, d)
Description: Calculates the p-value for a 2x2 chi-square test with Yates’ correction for continuity.
- Parameters:
	- a: The count in cell A1.
	- b: The count in cell A2.
	- c: The count in cell B1.
	- d: The count in cell B2.

Example:
```
=CHISQ2X2YATES(10, 20, 30, 40)
```

## Installation
### Windows
1. Download the add-in file from the releases page.
2. Open Excel and go to File > Options > Add-Ins
3. At the bottom, in the Manage box, select Excel Add-ins and click Go....
4. Click Browse... and locate the downloaded add-in file.
5. Click OK to load the add-in.

### Mac
1. Download the add-in file from the releases page.
2. Open Excel and go to Tools > Excel Add-Ins
3. Click Browse... and locate the downloaded add-in file.
4. Click OK to load the add-in.

## Usage

Once installed, you can use the **CHISQ2X2** and **CHISQ2X2YATES** functions in any cell within your Excel workbook. Simply enter the function with the appropriate parameters, and the p-value will be calculated for you.

### Examples

Without Yates’ Correction:
```
=CHISQ2X2(10, 20, 30, 40)
```
Returns: 0.372998484


With Yates' Correction:
```
=CHISQ2X2YATES(10, 20, 30, 40)
```
Returns: 0.504035866


### License
This project is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for more details.
