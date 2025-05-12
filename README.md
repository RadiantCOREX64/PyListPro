# PyListPro 🐍📋  
*A Python repository dedicated to mastering list operations!*  

---

## 📌 Overview  
This repository contains Python examples and exercises focused on **list operations**, including:  
- Sorting (`sort()`, `sorted()`)  
- Indexing and slicing  
- Appending, extending, and inserting (`append()`, `extend()`, `insert()`)  
- List comprehensions  
- Advanced manipulations (e.g., `zip()`, `map()`, `filter()`)  

Perfect for beginners learning Python or developers brushing up on core concepts.  

---

## 🚀 Quick Start  
1. **Clone the repo**:  
   ```bash
   git clone https://github.com/RadiantCOREx64/PyListPro.git
Navigate to a topic (e.g., sorting/) and run any Python file:

bash
python3 sorting/basic_sort.py
📂 Repository Structure
plaintext
PyListPro/
├── sorting/               # Sorting algorithms and examples
├── indexing/              # Index and slice operations  
├── list_methods/          # append(), extend(), etc.  
├── comprehensions/        # List/dict comprehensions  
└── advanced/              # zip(), map(), filter(), etc.  
💡 Example Code
🔄 Basic List Rotation
python
def rotate_list(lst, k):
    return lst[-k:] + lst[:-k]

print(rotate_list([1, 2, 3, 4, 5], 2))  # Output: [4, 5, 1, 2, 3]
📊 Sorting with Custom Keys
python
users = [{"name": "Alice", "age": 25}, {"name": "Bob", "age": 30}]
sorted_users = sorted(users, key=lambda x: x["age"], reverse=True)
print(sorted_users)  # Output: [{'name': 'Bob', 'age': 30}, {'name': 'Alice', 'age': 25}]
🤝 Contributing
Contributions welcome! Open an issue or submit a PR for:

New list operation examples

Optimizations or fixes

Creative use cases

📜 License
MIT © Sina Parsa
