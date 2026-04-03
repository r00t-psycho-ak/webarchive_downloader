
python3 webarchive_downloader.py -f <input_file> -o <output_file>

Parameters
- -f, --file: Input file containing root domains (one domain per line).
- -o, --output: Output file where all results will be saved.

### Example
```bash
python3 webarchive_downloader.py -f root.txt -o allresult.txt
```

Here, `root.txt` contains the list of domains, and the results will be saved in `allresult.txt`

### Input File Format
The input file should list one root domain per line, e.g.:
`example.com
testsite.org
demo.net` 

### Output
The output file will contain all URLs and parameters retrieved from web.archive.org, one per line.

## Notes
-   The script appends results to the output file if it already exists.
-   The script skips empty lines in the input file.

## Installation
1.  Clone the repository:
 `git clone https://github.com/r00t-psycho-ak/webarchive_downloader.git
 cd web-archive-downloader` 
  
2.  Install dependencies:
```bash
 `pip install requests` 
  ```
## License
This project is licensed under the MIT License.
## Contributions
Contributions are welcome! Feel free to submit a pull request or open an issue.
## Disclaimer
Use this script responsibly and only on domains you have permission to test.

 `You can upload both the script and README to your GitHub repository. Let me know if you need
 `
