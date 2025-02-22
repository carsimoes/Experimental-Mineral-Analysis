Factorial Design in Mineral Hardness Experiment

Overview

This project applies factorial design to study how temperature and acid exposure affect the hardness of minerals. Using a dataset of minerals, we introduce controlled experimental conditions and modify hardness values based on scientific principles.

Dataset

The dataset includes mineral properties such as:

Mineral Name

Mohs Hardness (original)

Experimental Conditions:

Temperature Levels: Low (25°C), Medium (200°C), High (800°C)

Acid Exposure: No Acid (pH 7), Weak Acid (pH 5), Strong Acid (pH 1)

Experimental Hardness (adjusted based on conditions)

Methodology

Assign Experimental Conditions

Randomly assign each mineral to a temperature and acid exposure level.

Adjust Hardness Scientifically

Temperature Effect: Higher temperatures may decrease hardness due to phase transitions.

Acid Effect: Reactive minerals (e.g., calcite, gypsum) see a reduction in hardness under acidic conditions.

Save Modified Dataset

The new dataset (minerals_experimental.csv) contains the experimental hardness values.

Installation

# Clone the repository
git clone https://github.com/yourusername/Factorial-Design-Minerals.git
cd Factorial-Design-Minerals

# Install dependencies
pip install pandas numpy

Usage

Run the script to generate the experimental dataset:

python factorial_design_minerals.py

Sample Output

    Mineral_Name  Hardness Temperature  Acid_Exposure  Experimental_Hardness
0        Quartz      7.00       Medium       No Acid                  6.65
1        Calcite      3.00        High   Strong Acid                  1.79
2        Feldspar     6.00         Low    Weak Acid                  6.00
3        Gypsum      2.00       Medium   Strong Acid                  1.26
4        Talc        1.00        High       No Acid                  0.85

Contributing

Feel free to fork the repository and suggest improvements via pull requests.

License

This project is open-source under the MIT License.
