# Stefan Agapie
---

## **Summary Statement**
    I have over two decades of software development experience. I'm currently focused on writting back-end services
    in Python using FastAPI, SQLAlchemy and Docker containerization.

---

## **Work Experience**
```
Software Engineer
Eigen Technologies
April 2022 - Present
New York, NY 10001
  - Develop plugins for our AI platform that enhance existing or extends the system's capabilities of extracting 
    text from documents that are answers two client constructed queries
  - Develop space and time effiecnt code to lower computing cost and improve waiting time of text processing
  - Develop Python code that is modular for increased reusability across multiple client solutions to lower cost
  - Develop Python code that is testable by taking a TDD approach to ensure accurate results
  - Build custom REST APIs to allow custom integration with our client services
  - Deliver solutions by build and running containerized services for clients
  - Mentor enginners in developing modular, testable and efficient software in a pair programming setting
```
```
Automation Engineer
New Classrooms
May 2018 - Apr 2022
New York, NY 10001
  - Develop Python code to perform software verification by generating random input and computed expected output 
    data with constrained specifications as per requirements
  - Automate manual product operations that resulted in faster turnaround time thus increasing productivity
  - Automate manual database operations that where prone to error and labor intensive such as databse migrations 
    and synchronizations
  - Automate manual frontend tests, end-to-end tests, REST API tests and increse the scope and depth of testing 
    by several orders of magnitude
  - Increase the number of bug reports by several orders of magnitude thus resulting in a stabler product
  - Work with business analysts to improve functional requirement documentation by performing formal requirements 
    verification and minimizing ambiguity while striving to find the correct level of granularity
  - Mentor automation engineers in engineering best practices
```
    
---

## **Contact**
Run `$ python -m contact` or use the flowchart to construct the email

```python title="contact.py" linenums="1"
def get_contact():
    c = {4: "com", 1: "agapie", 0: "stefan", 2: "contact", 3: "gmail"}
    return f"{c[0]}.{c[1]}.{c[2]}@{c[3]}.{c[4]}"

if __name__ == '__main__':
    print(get_contact())
```
``` mermaid
graph LR
  A[Start] --> B{1+1=3?};
  B -->|Yes| C["burnt.toast.fried"];
  B -->|No| D["stefan.agapie.contact"];
  C --> E{1-1=0?};
  D --> E;
  E -->|Yes| F["@gmail.com"];
  E -->|No| G["@pickle.gov"];
```