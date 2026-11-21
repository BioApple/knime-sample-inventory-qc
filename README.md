# Sample inventory QC workflow

This KNIME workflow identifies sample IDs recorded at multiple storage locations. It counts each distinct location once per sample ID.

[Read the illustrated user guide](Sample%20inventory%20guide.pdf)

## Run the example

1. Extract the ZIP. The extracted folder contains Sample_inventory_QC, Input, and Output side by side.
2. With KNIME closed, copy these three folders together into a fresh local KNIME workspace folder. Open that workspace in KNIME Analytics Platform.
3. Open Sample_inventory_QC and select **Execute all**.
4. Open Output. The file unique_ids.csv lists samples with one location. The file not_unique_ids.csv lists samples with multiple locations.

For another run, move the two previous result files out of Output first. To use another inventory, place it in Input with the filename sample_inventory.csv and the same column headers.
