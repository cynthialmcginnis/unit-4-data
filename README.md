# What the Data Teaches

An interactive lecture and a hands-on lab sprint on data selection and preparation for artificial intelligence (AI). Both run in a web browser with nothing to install.

**Live site:** https://cynthialmcginnis.github.io/unit-4-data/

## What is here

| File | What it is |
|---|---|
| `index.html` | Landing page that links to the lecture and the sprint |
| `lecture.html` | The lecture: a page-turning book with interactive checks, two 3D views, and a capstone workshop at the end |
| `sprint.html` | The AI Lab Sprint, *Right AI, Right Data* |

## The lecture

Six sections:

1. Different problems need different data
2. Five dimensions of data quality (accuracy, completeness, consistency, timeliness, representativeness)
3. Where bias hides in data (selection, representation, measurement, historical, proxy)
4. Preprocessing: missing values, outliers, scaling, encoding, and building new input variables
5. Training, validation, and test sets, and how leaks happen
6. Testing a dataset before you trust it: profiling, cross-validation, and a vendor's score

A capstone workshop follows. Students work in groups of three and leave with four written answers for their own project: the problem, the variables, the type of AI, and the AI tool. The **My capstone plan** page saves as students type and downloads as a text file.

**Pick a student** chooses a name at random and does not repeat a name until everyone has been picked. Use **Class list** to type in your students' first names. The list saves only in your own browser. No student names are stored in this repository.

## The AI Lab Sprint: Right AI, Right Data

Teams at two sites each work through at least three of five made-up organizations. Every case has four parts:

- **Part A:** Pick the type of AI from a list of 11 and explain why it fits the problem.
- **Part B:** Pick the AI tool from a list of 18 and explain how it fits the data.
- **Part C:** Pick one data quality dimension and one type of data bias to check, and explain why each could show up.
- **Part D: Test it on data.** Seven cases come with mock data. Students pick the output variable, the input variables, and the type of AI, then run a real model in the browser. A choice that does not fit is blocked with a plain message that says what to change. A choice that fits trains a model and shows a chart of what that type of AI does. Students then explain what the result means for the organization's problem before they can compare their thinking with an analyst's conclusions.

The models are small and written for teaching: a decision tree and naive Bayes for classification, linear regression for regression and forecasting, k-means for clustering, a frequency-based score for anomaly detection, next-item counts for recommendation, and a word list for sentiment. The mock data is generated in the page with a fixed seed, so every laptop sees the same data. Each dataset can be downloaded as a comma-separated values (CSV) file.

At the end, each team briefs the other site on one case and prints its report as a PDF (Portable Document Format) file. A paper version prints for students without a device.

## Use it

Open the live site, or download the files and open `index.html` in any modern browser. The lecture's 3D views and the fonts load from the internet. Everything else works offline.

To host your own copy, fork this repository and turn on GitHub Pages under **Settings > Pages**, using the `main` branch.

## Privacy

Nothing is sent to a server. Team names, answers, and the class list save only in the browser on the device where they were typed.

## License

MIT License. See `LICENSE`.

Created by Cynthia McGinnis.
