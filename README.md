# CCCS 106 - Week 5 Laboratory Task

## CSPC Scholarship Intake Portal

## 1. About the Laboratory Task

This laboratory task is our Week 5 activity for **CCCS 106: Application Development and Emerging Technologies**.

The CSPC Scholarship Intake Portal is a simple scholarship form made using Python and Flet. It checks the information entered by the user and shows an error message when something is wrong. It also prevents the application from crashing when invalid data is entered.

## 2. Group Members

**Group 05**
**BSCS 3A**

* Bongalos, Joshua Benedict 
* Pontanal, Jake Laurence
* Mangente, Kurt Hearick

## 3. Laboratory Task Features

* Scholarship application form
* Name validation
* Student ID validation
* CSPC email validation
* Mobile number validation
* GWA validation
* Scholarship program selection
* Error messages for invalid inputs
* Error messages clear while typing
* Success message after a valid application
* Application counter
* Recent application records
* Automated tests

## 4. Validation Rules

| Field               | Rule                                                                       |
| ------------------- | -------------------------------------------------------------------------- |
| Applicant Name      | Must be 2–60 characters and use valid letters, spaces, hyphens, or periods |
| Student ID          | Must follow the `YYYY-NNNN` format                                         |
| CSPC Email          | Must end with `@cspc.edu.ph`                                               |
| Mobile Number       | Must follow `09XXXXXXXXX` or `+639XXXXXXXXX`                               |
| GWA                 | Must be a number from `1.00` to `5.00`                                     |
| Scholarship Program | A scholarship program must be selected                                     |

The system also handles wrong or non-number GWA inputs without crashing.

## 5. Technologies Used

* Python 3.12+
* Flet 0.86.5
* Git
* GitHub
* Python unittest

## 6. How to Run

Make sure Python and Flet are installed first.

To run the application:

```bash
python scholarship_portal.py
```

To run the automated tests:

```bash
python test_validation.py -v
```

## 7. Automated Test Result

We made automated tests to check if the validation functions are working correctly.

There are **14 tests**, and all of them passed.

```text
----------------------------------------------------------------------
Ran 14 tests in 0.082s

OK
```

## 8. Repository / Collaboration Info

**GitHub Repository:** `jbbongalos/cccs106-lab-form-validation-group05`

We worked on this laboratory task as a group using GitHub. We used branches and pull requests so each member could work on their assigned part. After merging our work, we tested the final `main` branch.

### Contributions

* **Bongalos, Joshua Benedict** - Flet UI and application flow
* **Pontanal, Jake Laurence** - Validation and testing
* **Mangente, Kurt Hearick** - Automated tests and validation support

---

**CCCS 106 - Application Development and Emerging Technologies**
**BSCS 3A | Group 05**
