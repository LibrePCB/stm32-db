# STM32 Pinout

This repository contains a collection of scripts to extract STM32 MCU
information files (including pin mappings and signals) in JSON format from the
STM32CubeMX database.


## Usage

1. Download and install [STM32CubeMX][stm32cubemx] ([direct link][stm32cubemx-direct])

2. Unpack the ZIP file to a writable directory on your computer

3. Run `python3 extract.py --db path/to/stm32cubemx/db/mcu/`

[stm32cubemx]: https://www.st.com/en/development-tools/stm32cubemx.html#get-software
[stm32cubemx-direct]: https://sw-center.st.com/packs/resource/library/stm32cube_mx_v550.zip


## Data

See JSON files in `data/` directory.


## License

The scripts are licensed under the MIT license, see `LICENSE.txt` file.

The data files are generated by using STM32CubeMX. They only contain technical
information that could also be obtained from the datasheets and *probably* do
not fall under copyright.
