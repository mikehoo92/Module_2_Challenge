# Loan Qualifier Application
## *Saving QUalifying Loans*

This project will give users the option to save any qualifying loans found based on their information. The qualifying loans will be saved in a new file so that they could be tracked for the user to compare options


---

## Technologies

This project uses python 3.7 with the following packages:

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

* [pytest](https://docs.pytest.org/en/stable/) - For basic assertion testing of financial calculators and filters, and filio.

---

## Installation Guide

For this program to run succesfully we ask that you install fire, questionary, and pytest.

```
pip install fire
pip install questionary
pip install pytest
```

---

## Usage

To execute this program, please start by downloading the zip file. From there, app.py could be run to initially ask for a file path to access all loan types. The program will then ask for the user's information and from that determine how many qualifying loans exist. Refer to the sreenshot below.

![Loan Qualifier Prompts](Images/loan_qalifier.png)

The user will then be asked if they would like to save the qualifying loans. If yes, they will be asked to provide an output path to save the qualifying loans to. 

---

## Contributors

Michael Husary was the main contributer along with fellow classmates and the educational staff. 

---

## License

MIT
