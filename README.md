# AI-ML-Learning-RodMap

# 🐍 Python Programming সম্পূর্ণ গাইডলাইন (AI/ML Engineer হওয়ার জন্য)

## 📋 সূচিপত্র

text

    ১. Python পরিচিতি
    ২. Learning Roadmap (১২ মাসের প্ল্যান)
    ৩. Phase-wise বিস্তারিত শিক্ষা
    ৪. AI/ML এর জন্য বিশেষ দক্ষতা
    ৫. প্রজেক্ট আইডিয়া
    ৬. রিসোর্স ও টুলস

---

## 🎯 Phase 1: Python Basics (মাস ১-২)

### সপ্তাহ ১-২: Python Setup ও পরিচিতি

Python

    # Python কি?
    """
    Python হলো একটি high-level, interpreted programming language।
    এটি সহজ syntax এর কারণে beginners এর জন্য সবচেয়ে ভালো।

    কেন Python শিখবেন?
    ✅ সহজ ও readable syntax
    ✅ AI/ML এর জন্য সবচেয়ে জনপ্রিয়
    ✅ বিশাল library support
    ✅ বড় community
    ✅ চাকরির বাজারে high demand
    """

    # প্রথম প্রোগ্রাম
    print("হ্যালো, আমি Python শিখছি!")
    print("আমি AI/ML Engineer হতে চাই!")

### ইনস্টলেশন গাইড:

text

    ধাপ ১: Python ডাউনলোড করুন
            👉 https://www.python.org/downloads/

    ধাপ ২: Install করার সময় "Add Python to PATH" চেক করুন

    ধাপ ৩: VS Code বা PyCharm ইনস্টল করুন
            👉 VS Code: https://code.visualstudio.com/

    ধাপ ৪: Terminal এ যাচাই করুন:
            python --version

---

### সপ্তাহ ৩-৪: Variables ও Data Types

Python

    # ============================================
    # Variables (ভেরিয়েবল) - ডেটা সংরক্ষণের জায়গা
    # ============================================

    # String (টেক্সট)
    naam = "রাহিম"
    bortoman_kaj = "Python শিখছি"

    # Integer (পূর্ণ সংখ্যা)
    boyos = 22
    bochor = 2024

    # Float (দশমিক সংখ্যা)
    cgpa = 3.75
    height = 5.8

    # Boolean (সত্য/মিথ্যা)
    student = True
    chutti = False

    # ভেরিয়েবল প্রিন্ট করা
    print(f"আমার নাম {naam}")
    print(f"আমার বয়স {boyos} বছর")
    print(f"আমার CGPA {cgpa}")

    # ============================================
    # Data Type চেক করা
    # ============================================
    print(type(naam))      # <class 'str'>
    print(type(boyos))     # <class 'int'>
    print(type(cgpa))      # <class 'float'>
    print(type(student))   # <class 'bool'>

### সপ্তাহ ৫-৬: Operators (অপারেটর)

Python

    # ============================================
    # Arithmetic Operators (গাণিতিক অপারেটর)
    # ============================================

    a = 15
    b = 4

    print(f"যোগ: {a} + {b} = {a + b}")           # 19
    print(f"বিয়োগ: {a} - {b} = {a - b}")         # 11
    print(f"গুণ: {a} * {b} = {a * b}")           # 60
    print(f"ভাগ: {a} / {b} = {a / b}")           # 3.75
    print(f"পূর্ণ ভাগ: {a} // {b} = {a // b}")   # 3
    print(f"ভাগশেষ: {a} % {b} = {a % b}")        # 3
    print(f"পাওয়ার: {a} ** {b} = {a ** b}")     # 50625

    # ============================================
    # Comparison Operators (তুলনামূলক অপারেটর)
    # ============================================

    x = 10
    y = 20

    print(f"{x} == {y}: {x == y}")   # False (সমান কিনা)
    print(f"{x} != {y}: {x != y}")   # True (অসমান কিনা)
    print(f"{x} > {y}: {x > y}")     # False (বড় কিনা)
    print(f"{x} < {y}: {x < y}")     # True (ছোট কিনা)
    print(f"{x} >= {y}: {x >= y}")   # False (বড় বা সমান)
    print(f"{x} <= {y}: {x <= y}")   # True (ছোট বা সমান)

    # ============================================
    # Logical Operators (যৌক্তিক অপারেটর)
    # ============================================

    age = 25
    has_license = True

    # and - দুটোই সত্য হতে হবে
    print(age >= 18 and has_license)  # True

    # or - যেকোনো একটা সত্য হলেই হবে
    print(age < 18 or has_license)    # True

    # not - উল্টো করে দেয়
    print(not has_license)            # False

### সপ্তাহ ৭-৮: Strings (স্ট্রিং)

Python

    # ============================================
    # String তৈরি করা
    # ============================================

    # বিভিন্নভাবে string তৈরি
    text1 = 'Single quote এ string'
    text2 = "Double quote এ string"
    text3 = '''Multiple
    line
    string'''

    # ============================================
    # String Operations
    # ============================================

    basha = "বাংলাদেশ"
    programming = "Python Programming"

    # দৈর্ঘ্য বের করা
    print(f"দৈর্ঘ্য: {len(programming)}")  # 18

    # বড় হাতের অক্ষরে
    print(programming.upper())  # PYTHON PROGRAMMING

    # ছোট হাতের অক্ষরে
    print(programming.lower())  # python programming

    # প্রতিস্থাপন
    print(programming.replace("Python", "Java"))  # Java Programming

    # বিভাজন
    words = programming.split(" ")
    print(words)  # ['Python', 'Programming']

    # ============================================
    # String Indexing ও Slicing
    # ============================================

    text = "BANGLADESH"

    # Indexing (অবস্থান অনুযায়ী অক্ষর)
    print(f"প্রথম অক্ষর: {text[0]}")     # B
    print(f"শেষ অক্ষর: {text[-1]}")     # H

    # Slicing (অংশ কেটে নেওয়া)
    print(f"প্রথম ৪টি: {text[0:4]}")    # BANG
    print(f"শেষ ৪টি: {text[-4:]}")      # DESH

    # ============================================
    # String Formatting (গুরুত্বপূর্ণ!)
    # ============================================

    naam = "করিম"
    boyos = 25
    cgpa = 3.85

    # f-string (সবচেয়ে আধুনিক পদ্ধতি)
    print(f"আমার নাম {naam}, বয়স {boyos}, CGPA {cgpa:.2f}")

    # format() method
    print("আমার নাম {}, বয়স {}".format(naam, boyos))

    # % formatting (পুরনো পদ্ধতি)
    print("আমার নাম %s, বয়স %d" % (naam, boyos))

---

## 🎯 Phase 2: Control Flow ও Functions (মাস ২-৩)

### সপ্তাহ ৯-১০: Conditional Statements

Python

    # ============================================
    # if-elif-else স্টেটমেন্ট
    # ============================================

    # উদাহরণ ১: পরীক্ষার গ্রেড নির্ণয়
    marks = 75

    if marks >= 80:
        grade = "A+"
        print("অসাধারণ! তুমি A+ পেয়েছ! 🎉")
    elif marks >= 70:
        grade = "A"
        print("চমৎকার! তুমি A পেয়েছ! 👍")
    elif marks >= 60:
        grade = "B"
        print("ভালো! তুমি B পেয়েছ!")
    elif marks >= 50:
        grade = "C"
        print("মোটামুটি! তুমি C পেয়েছ!")
    elif marks >= 40:
        grade = "D"
        print("পাস করেছ!")
    else:
        grade = "F"
        print("ফেল! আরো পড়াশোনা করো! 📚")

    print(f"তোমার গ্রেড: {grade}")

    # ============================================
    # উদাহরণ ২: লিপ ইয়ার চেক করা
    # ============================================

    year = 2024

    if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
        print(f"{year} একটি লিপ ইয়ার! 📅")
    else:
        print(f"{year} লিপ ইয়ার নয়!")

    # ============================================
    # উদাহরণ ৩: বয়স অনুযায়ী ক্যাটাগরি
    # ============================================

    age = int(input("আপনার বয়স লিখুন: "))

    if age < 0:
        print("বয়স নেগেটিভ হতে পারে না!")
    elif age < 13:
        print("তুমি একজন শিশু! 👶")
    elif age < 20:
        print("তুমি একজন কিশোর! 🧒")
    elif age < 60:
        print("তুমি একজন প্রাপ্তবয়স্ক! 🧑")
    else:
        print("তুমি একজন বয়স্ক ব্যক্তি! 👴")

    # ============================================
    # Nested if (এক if এর মধ্যে আরেক if)
    # ============================================

    username = "admin"
    password = "12345"

    input_user = input("Username: ")
    input_pass = input("Password: ")

    if input_user == username:
        if input_pass == password:
            print("লগইন সফল! ✅")
        else:
            print("ভুল পাসওয়ার্ড! ❌")
    else:
        print("ভুল ইউজারনেম! ❌")

    # ============================================
    # Ternary Operator (শর্টকাট if-else)
    # ============================================

    age = 18
    status = "প্রাপ্তবয়স্ক" if age >= 18 else "অপ্রাপ্তবয়স্ক"
    print(f"আপনি {status}")

### সপ্তাহ ১১-১২: Loops (লুপ)

Python

    # ============================================
    # for loop - নির্দিষ্ট সংখ্যকবার চালানো
    # ============================================

    # উদাহরণ ১: ১ থেকে ১০ পর্যন্ত প্রিন্ট
    print("১ থেকে ১০ পর্যন্ত সংখ্যা:")
    for i in range(1, 11):
        print(i, end=" ")
    print()  # নতুন লাইন

    # উদাহরণ ২: তালিকার প্রতিটি আইটেম প্রিন্ট
    fruits = ["আম", "কাঁঠাল", "লিচু", "জাম", "কলা"]
    print("\nবাংলাদেশের ফল:")
    for fruit in fruits:
        print(f"🍎 {fruit}")

    # উদাহরণ ৩: নামতা (Multiplication Table)
    number = 5
    print(f"\n{number} এর নামতা:")
    for i in range(1, 11):
        result = number * i
        print(f"{number} × {i} = {result}")

    # ============================================
    # range() ফাংশন বিস্তারিত
    # ============================================

    # range(stop) - 0 থেকে stop-1 পর্যন্ত
    print("\nrange(5):", list(range(5)))  # [0, 1, 2, 3, 4]

    # range(start, stop) - start থেকে stop-1 পর্যন্ত
    print("range(1, 6):", list(range(1, 6)))  # [1, 2, 3, 4, 5]

    # range(start, stop, step) - step করে করে
    print("range(0, 10, 2):", list(range(0, 10, 2)))  # [0, 2, 4, 6, 8]

    # উল্টো গণনা
    print("range(10, 0, -1):", list(range(10, 0, -1)))  # [10, 9, 8, ..., 1]

    # ============================================
    # while loop - শর্ত সত্য থাকা পর্যন্ত চলবে
    # ============================================

    # উদাহরণ ১: ১ থেকে ৫ পর্যন্ত
    print("\nwhile loop দিয়ে ১-৫:")
    count = 1
    while count <= 5:
        print(count, end=" ")
        count += 1
    print()

    # উদাহরণ ২: পাসওয়ার্ড চেক (সঠিক না হওয়া পর্যন্ত)
    correct_password = "python123"
    attempts = 3

    while attempts > 0:
        password = input(f"\nপাসওয়ার্ড দিন ({attempts} চেষ্টা বাকি): ")
        if password == correct_password:
            print("সঠিক পাসওয়ার্ড! ✅")
            break
        else:
            attempts -= 1
            print("ভুল পাসওয়ার্ড! ❌")

    if attempts == 0:
        print("সব চেষ্টা শেষ! অ্যাকাউন্ট লক! 🔒")

    # ============================================
    # break, continue, else
    # ============================================

    # break - লুপ থেকে বের হয়ে যাওয়া
    print("\nbreak এর উদাহরণ:")
    for i in range(1, 10):
        if i == 5:
            print("৫ পাওয়া গেছে, থামছি!")
            break
        print(i, end=" ")

    # continue - পরবর্তী iteration এ চলে যাওয়া
    print("\n\ncontinue এর উদাহরণ (জোড় সংখ্যা বাদ):")
    for i in range(1, 11):
        if i % 2 == 0:  # জোড় হলে skip
            continue
        print(i, end=" ")

    # else with loop - লুপ সম্পূর্ণ হলে else চলবে
    print("\n\nelse এর উদাহরণ:")
    for i in range(3):
        print(i)
    else:
        print("লুপ সম্পূর্ণ হয়েছে!")

    # ============================================
    # Nested Loop (এক loop এর মধ্যে আরেক loop)
    # ============================================

    # প্যাটার্ন প্রিন্ট
    print("\nতারার প্যাটার্ন:")
    for i in range(1, 6):
        for j in range(i):
            print("*", end=" ")
        print()

    # Output:
    # *
    # * *
    # * * *
    # * * * *
    # * * * * *

### সপ্তাহ ১৩-১৬: Functions (ফাংশন)

Python

    # ============================================
    # Function কি? - পুনরায় ব্যবহারযোগ্য কোড ব্লক
    # ============================================

    # সাধারণ ফাংশন
    def salam():
        """এই ফাংশন সালাম দেয়"""
        print("আসসালামু আলাইকুম! 🙏")

    # ফাংশন কল করা
    salam()

    # ============================================
    # Parameter সহ ফাংশন
    # ============================================

    def personalized_salam(naam):
        """নাম সহ সালাম দেয়"""
        print(f"আসসালামু আলাইকুম, {naam}! 🙏")

    personalized_salam("করিম")
    personalized_salam("রহিম")

    # ============================================
    # Multiple Parameters
    # ============================================

    def introduce(naam, boyos, pesah):
        """ব্যক্তির পরিচয় দেয়"""
        print(f"আমার নাম {naam}")
        print(f"আমার বয়স {boyos} বছর")
        print(f"আমি একজন {pesah}")
        print("-" * 30)

    introduce("আহমেদ", 25, "সফটওয়্যার ইঞ্জিনিয়ার")
    introduce("ফাতেমা", 22, "ডাটা সায়েন্টিস্ট")

    # ============================================
    # Return Value (ফেরত মান)
    # ============================================

    def add(a, b):
        """দুটি সংখ্যা যোগ করে"""
        return a + b

    def subtract(a, b):
        """দুটি সংখ্যা বিয়োগ করে"""
        return a - b

    def multiply(a, b):
        """দুটি সংখ্যা গুণ করে"""
        return a * b

    def divide(a, b):
        """দুটি সংখ্যা ভাগ করে"""
        if b == 0:
            return "শূন্য দিয়ে ভাগ করা যায় না!"
        return a / b

    # ফাংশন ব্যবহার
    result = add(10, 5)
    print(f"যোগফল: {result}")
    print(f"বিয়োগফল: {subtract(10, 5)}")
    print(f"গুণফল: {multiply(10, 5)}")
    print(f"ভাগফল: {divide(10, 5)}")

    # ============================================
    # Default Parameters (ডিফল্ট মান)
    # ============================================

    def greet(naam, message="শুভ সকাল"):
        """ডিফল্ট message সহ অভিবাদন"""
        print(f"{message}, {naam}!")

    greet("করিম")                    # শুভ সকাল, করিম!
    greet("রহিম", "শুভ সন্ধ্যা")      # শুভ সন্ধ্যা, রহিম!

    # ============================================
    # *args (অসীম সংখ্যক arguments)
    # ============================================

    def total(*numbers):
        """যেকোনো সংখ্যক সংখ্যার যোগফল"""
        result = 0
        for num in numbers:
            result += num
        return result

    print(f"মোট: {total(1, 2, 3)}")           # 6
    print(f"মোট: {total(1, 2, 3, 4, 5)}")     # 15
    print(f"মোট: {total(10, 20)}")            # 30

    # ============================================
    # **kwargs (Keyword Arguments)
    # ============================================

    def student_info(**info):
        """শিক্ষার্থীর তথ্য প্রিন্ট করে"""
        print("=" * 30)
        for key, value in info.items():
            print(f"{key}: {value}")

    student_info(naam="আহমেদ", roll=101, class_name="দশম")
    student_info(naam="ফাতেমা", roll=102, class_name="দশম", section="A")

    # ============================================
    # Lambda Function (এক লাইনের ফাংশন)
    # ============================================

    # সাধারণ ফাংশন
    def square(x):
        return x ** 2

    # Lambda হিসেবে
    square_lambda = lambda x: x ** 2

    print(f"বর্গ (সাধারণ): {square(5)}")
    print(f"বর্গ (lambda): {square_lambda(5)}")

    # Lambda এর ব্যবহার - sorting এ
    students = [
        {"naam": "আহমেদ", "marks": 85},
        {"naam": "করিম", "marks": 92},
        {"naam": "রহিম", "marks": 78}
    ]

    # marks অনুযায়ী সাজানো
    students.sort(key=lambda x: x["marks"], reverse=True)
    print("\nমার্কস অনুযায়ী সাজানো:")
    for s in students:
        print(f"{s['naam']}: {s['marks']}")

    # ============================================
    # Recursive Function (নিজেকে কল করা)
    # ============================================

    def factorial(n):
        """n এর ফ্যাক্টোরিয়াল বের করে"""
        if n == 0 or n == 1:
            return 1
        else:
            return n * factorial(n - 1)

    def fibonacci(n):
        """n তম ফিবোনাচি সংখ্যা"""
        if n <= 1:
            return n
        else:
            return fibonacci(n-1) + fibonacci(n-2)

    print(f"\n5! = {factorial(5)}")  # 120
    print(f"10! = {factorial(10)}") # 3628800

    print("\nফিবোনাচি সিরিজ (প্রথম ১০টি):")
    for i in range(10):
        print(fibonacci(i), end=" ")

---

## 🎯 Phase 3: Data Structures (মাস ৩-৪)

### সপ্তাহ ১৭-১৮: Lists (তালিকা)

Python

    # ============================================
    # List তৈরি করা
    # ============================================

    # খালি list
    empty_list = []

    # সংখ্যার list
    numbers = [1, 2, 3, 4, 5]

    # মিশ্র list
    mixed = [1, "hello", 3.14, True, None]

    # বাংলাদেশের বিভাগ
    divisions = ["ঢাকা", "চট্টগ্রাম", "রাজশাহী", "খুলনা",
                 "বরিশাল", "সিলেট", "রংপুর", "ময়মনসিংহ"]

    print(f"বিভাগের সংখ্যা: {len(divisions)}")

    # ============================================
    # List Indexing ও Slicing
    # ============================================

    fruits = ["আম", "কাঁঠাল", "লিচু", "জাম", "কলা", "পেয়ারা"]

    print(f"প্রথম ফল: {fruits[0]}")      # আম
    print(f"শেষ ফল: {fruits[-1]}")       # পেয়ারা
    print(f"২য় থেকে ৪র্থ: {fruits[1:4]}")  # ['কাঁঠাল', 'লিচু', 'জাম']
    print(f"প্রথম ৩টি: {fruits[:3]}")     # ['আম', 'কাঁঠাল', 'লিচু']
    print(f"শেষ ২টি: {fruits[-2:]}")      # ['কলা', 'পেয়ারা']

    # ============================================
    # List Methods (গুরুত্বপূর্ণ!)
    # ============================================

    shopping_list = ["চাল", "ডাল", "তেল"]
    print(f"শুরুতে: {shopping_list}")

    # append() - শেষে যোগ করা
    shopping_list.append("লবণ")
    print(f"append() এর পর: {shopping_list}")

    # insert() - নির্দিষ্ট স্থানে যোগ করা
    shopping_list.insert(1, "চিনি")
    print(f"insert() এর পর: {shopping_list}")

    # extend() - অন্য list যোগ করা
    more_items = ["মসলা", "পেঁয়াজ"]
    shopping_list.extend(more_items)
    print(f"extend() এর পর: {shopping_list}")

    # remove() - নির্দিষ্ট আইটেম বাদ দেওয়া
    shopping_list.remove("তেল")
    print(f"remove() এর পর: {shopping_list}")

    # pop() - শেষ আইটেম বাদ দিয়ে return করা
    last_item = shopping_list.pop()
    print(f"pop() এর পর: {shopping_list}")
    print(f"বাদ দেওয়া আইটেম: {last_item}")

    # ============================================
    # List Sorting
    # ============================================

    numbers = [64, 34, 25, 12, 22, 11, 90]

    # sort() - original list পরিবর্তন করে
    numbers.sort()
    print(f"ছোট থেকে বড়: {numbers}")

    numbers.sort(reverse=True)
    print(f"বড় থেকে ছোট: {numbers}")

    # sorted() - নতুন list return করে
    names = ["জামাল", "করিম", "আহমেদ", "বাবু"]
    sorted_names = sorted(names)
    print(f"সাজানো নাম: {sorted_names}")

    # ============================================
    # List Comprehension (এক লাইনে list তৈরি)
    # ============================================

    # সাধারণ পদ্ধতি
    squares = []
    for i in range(1, 11):
        squares.append(i ** 2)
    print(f"বর্গ (সাধারণ): {squares}")

    # List Comprehension
    squares = [i ** 2 for i in range(1, 11)]
    print(f"বর্গ (comprehension): {squares}")

    # শর্ত সহ
    even_squares = [i ** 2 for i in range(1, 11) if i % 2 == 0]
    print(f"জোড় সংখ্যার বর্গ: {even_squares}")

    # ============================================
    # Nested List (দ্বিমাত্রিক list - Matrix)
    # ============================================

    matrix = [
        [1, 2, 3],
        [4, 5, 6],
        [7, 8, 9]
    ]

    print("Matrix:")
    for row in matrix:
        print(row)

    # নির্দিষ্ট element access
    print(f"\n২য় সারি, ৩য় কলাম: {matrix[1][2]}")  # 6

    # ============================================
    # প্র্যাক্টিকাল উদাহরণ: শিক্ষার্থীদের মার্কস
    # ============================================

    students = [
        {"naam": "আহমেদ", "marks": 85},
        {"naam": "করিম", "marks": 92},
        {"naam": "রহিম", "marks": 78},
        {"naam": "জামাল", "marks": 88},
        {"naam": "বাবু", "marks": 95}
    ]

    # সর্বোচ্চ মার্কস
    highest = max(students, key=lambda x: x["marks"])
    print(f"সর্বোচ্চ মার্কস: {highest['naam']} ({highest['marks']})")

    # গড় মার্কস
    average = sum(s["marks"] for s in students) / len(students)
    print(f"গড় মার্কস: {average:.2f}")

    # পাস করা শিক্ষার্থী (৪০ এর বেশি)
    passed = [s for s in students if s["marks"] >= 40]
    print(f"পাস করেছে: {len(passed)} জন")

### সপ্তাহ ১৯-২০: Tuples ও Sets

Python

    # ============================================
    # TUPLE - অপরিবর্তনীয় list
    # ============================================

    # Tuple তৈরি
    coordinates = (23.8103, 90.4125)  # ঢাকার coordinates
    colors = ("লাল", "সবুজ", "নীল")
    single_item = (42,)  # একটি item এর tuple (comma লাগবে)

    print(f"ঢাকার coordinates: {coordinates}")
    print(f"রঙ: {colors}")

    # Tuple Unpacking
    lat, lon = coordinates
    print(f"অক্ষাংশ: {lat}, দ্রাঘিমাংশ: {lon}")

    # Tuple immutable (পরিবর্তন করা যায় না)
    try:
        colors[0] = "হলুদ"  # এটা error দেবে
    except TypeError as e:
        print(f"Error: Tuple পরিবর্তন করা যায় না!")

    # Tuple Methods
    numbers = (1, 2, 3, 2, 4, 2, 5)
    print(f"2 কতবার আছে: {numbers.count(2)}")  # 3
    print(f"3 এর position: {numbers.index(3)}")  # 2

    # ============================================
    # কখন Tuple ব্যবহার করবেন?
    # ============================================
    """
    ✅ যখন data পরিবর্তন হবে না
    ✅ Dictionary এর key হিসেবে
    ✅ Function থেকে multiple value return
    ✅ List এর চেয়ে দ্রুত
    """

    # Function থেকে multiple value return
    def get_min_max(numbers):
        return min(numbers), max(numbers)

    data = [5, 2, 8, 1, 9, 3]
    minimum, maximum = get_min_max(data)
    print(f"সর্বনিম্ন: {minimum}, সর্বোচ্চ: {maximum}")

    # ============================================
    # SET - অনন্য items এর সংকলন
    # ============================================

    # Set তৈরি
    fruits = {"আম", "কাঁঠাল", "লিচু", "আম"}  # duplicate automatically removed
    print(f"ফল: {fruits}")  # আম একবারই থাকবে

    # List থেকে duplicate বাদ দেওয়া
    numbers = [1, 2, 2, 3, 3, 3, 4, 4, 4, 4]
    unique_numbers = list(set(numbers))
    print(f"অনন্য সংখ্যা: {unique_numbers}")

    # ============================================
    # Set Operations
    # ============================================

    set1 = {1, 2, 3, 4, 5}
    set2 = {4, 5, 6, 7, 8}

    # Union (সব একসাথে)
    print(f"Union: {set1 | set2}")  # {1, 2, 3, 4, 5, 6, 7, 8}
    print(f"Union: {set1.union(set2)}")

    # Intersection (সাধারণ items)
    print(f"Intersection: {set1 & set2}")  # {4, 5}
    print(f"Intersection: {set1.intersection(set2)}")

    # Difference (set1 এ আছে কিন্তু set2 এ নেই)
    print(f"Difference: {set1 - set2}")  # {1, 2, 3}

    # Symmetric Difference (যেগুলো শুধু একটাতে আছে)
    print(f"Symmetric Difference: {set1 ^ set2}")  # {1, 2, 3, 6, 7, 8}

    # ============================================
    # Set Methods
    # ============================================

    colors = {"লাল", "সবুজ", "নীল"}

    # add() - একটি item যোগ
    colors.add("হলুদ")
    print(f"add() এর পর: {colors}")

    # update() - একাধিক item যোগ
    colors.update(["কালো", "সাদা"])
    print(f"update() এর পর: {colors}")

    # remove() - item বাদ দেওয়া (না থাকলে error)
    colors.remove("কালো")
    print(f"remove() এর পর: {colors}")

    # discard() - item বাদ দেওয়া (না থাকলে error নয়)
    colors.discard("বেগুনি")  # error হবে না
    print(f"discard() এর পর: {colors}")

    # ============================================
    # প্র্যাক্টিকাল উদাহরণ: ভোটার যাচাই
    # ============================================

    registered_voters = {"করিম", "রহিম", "আহমেদ", "জামাল", "বাবু"}
    already_voted = set()

    def cast_vote(name):
        if name not in registered_voters:
            print(f"❌ {name} নিবন্ধিত ভোটার নয়!")
            return False
        if name in already_voted:
            print(f"❌ {name} ইতোমধ্যে ভোট দিয়েছে!")
            return False

        already_voted.add(name)
        print(f"✅ {name} এর ভোট গৃহীত হয়েছে!")
        return True

    cast_vote("করিম")   # ✅
    cast_vote("করিম")   # ❌ (আবার চেষ্টা)
    cast_vote("সালাম")  # ❌ (নিবন্ধিত নয়)

    print(f"\nমোট ভোট: {len(already_voted)}")
    print(f"বাকি ভোটার: {registered_voters - already_voted}")

### সপ্তাহ ২১-২৪: Dictionaries (অভিধান)

Python

    # ============================================
    # Dictionary - key-value pair
    # ============================================

    # Dictionary তৈরি
    student = {
        "naam": "আহমেদ হোসেন",
        "roll": 101,
        "class": "দশম",
        "section": "A",
        "gpa": 4.85,
        "subjects": ["বাংলা", "ইংরেজি", "গণিত", "বিজ্ঞান"]
    }

    print("শিক্ষার্থীর তথ্য:")
    print(f"নাম: {student['naam']}")
    print(f"রোল: {student['roll']}")
    print(f"GPA: {student['gpa']}")

    # ============================================
    # Dictionary Access Methods
    # ============================================

    # get() - key না থাকলে None বা default value
    print(student.get("phone", "নম্বর নেই"))  # নম্বর নেই

    # keys() - সব keys
    print(f"Keys: {list(student.keys())}")

    # values() - সব values
    print(f"Values: {list(student.values())}")

    # items() - key-value pairs
    for key, value in student.items():
        print(f"{key}: {value}")

    # ============================================
    # Dictionary Modification
    # ============================================

    # নতুন key-value যোগ করা
    student["phone"] = "01700000000"
    student["email"] = "ahmed@email.com"

    # value পরিবর্তন করা
    student["gpa"] = 4.90

    # একাধিক key-value যোগ/পরিবর্তন
    student.update({
        "address": "ঢাকা",
        "guardian": "করিম হোসেন"
    })

    print("\nআপডেটেড তথ্য:")
    for key, value in student.items():
        print(f"{key}: {value}")

    # ============================================
    # Dictionary থেকে item বাদ দেওয়া
    # ============================================

    # pop() - নির্দিষ্ট key বাদ দেওয়া
    removed = student.pop("email")
    print(f"\nবাদ দেওয়া: {removed}")

    # del - আরেকটি পদ্ধতি
    del student["phone"]

    # ============================================
    # Nested Dictionary
    # ============================================

    school = {
        "class_10": {
            "section_a": {
                "students": 45,
                "class_teacher": "আব্দুল করিম"
            },
            "section_b": {
                "students": 42,
                "class_teacher": "ফাতেমা বেগম"
            }
        },
        "class_9": {
            "section_a": {
                "students": 48,
                "class_teacher": "রহিম উদ্দিন"
            }
        }
    }

    # Nested access
    print(f"\n১০ম শ্রেণি, A সেকশনের শিক্ষক: {school['class_10']['section_a']['class_teacher']}")

    # ============================================
    # Dictionary Comprehension
    # ============================================

    # সংখ্যার বর্গ (key: value)
    squares = {x: x**2 for x in range(1, 6)}
    print(f"\nবর্গ: {squares}")  # {1: 1, 2: 4, 3: 9, 4: 16, 5: 25}

    # শর্ত সহ
    even_squares = {x: x**2 for x in range(1, 11) if x % 2 == 0}
    print(f"জোড় সংখ্যার বর্গ: {even_squares}")

    # ============================================
    # প্র্যাক্টিকাল উদাহরণ: শব্দ গণনা
    # ============================================

    text = "আমি বাংলায় গান গাই আমি বাংলার গান গাই"
    words = text.split()

    word_count = {}
    for word in words:
        if word in word_count:
            word_count[word] += 1
        else:
            word_count[word] = 1

    print("\nশব্দ গণনা:")
    for word, count in word_count.items():
        print(f"'{word}': {count} বার")

    # Counter ব্যবহার করে (সহজ পদ্ধতি)
    from collections import Counter
    word_count = Counter(words)
    print(f"\nসবচেয়ে বেশি: {word_count.most_common(2)}")

    # ============================================
    # প্র্যাক্টিকাল উদাহরণ: ফোনবুক
    # ============================================

    phonebook = {}

    def add_contact(name, number):
        phonebook[name] = number
        print(f"✅ {name} যোগ করা হয়েছে!")

    def search_contact(name):
        if name in phonebook:
            print(f"📞 {name}: {phonebook[name]}")
        else:
            print(f"❌ {name} পাওয়া যায়নি!")

    def delete_contact(name):
        if name in phonebook:
            del phonebook[name]
            print(f"🗑️ {name} মুছে ফেলা হয়েছে!")
        else:
            print(f"❌ {name} পাওয়া যায়নি!")

    def show_all():
        if phonebook:
            print("\n📱 সব কন্টাক্ট:")
            for name, number in phonebook.items():
                print(f"  {name}: {number}")
        else:
            print("📱 ফোনবুক খালি!")

    # ব্যবহার
    add_contact("করিম", "01711111111")
    add_contact("রহিম", "01722222222")
    add_contact("আহমেদ", "01733333333")
    show_all()
    search_contact("করিম")
    delete_contact("রহিম")
    show_all()

---

## 🎯 Phase 4: OOP - Object Oriented Programming (মাস ৫-৬)

### সপ্তাহ ২৫-২৮: Classes ও Objects

Python

    # ============================================
    # Class কি? - একটি blueprint/নকশা
    # Object কি? - Class থেকে তৈরি instance
    # ============================================

    # সাধারণ Class
    class Student:
        """শিক্ষার্থী class"""

        # Constructor (শুরুতে call হয়)
        def __init__(self, naam, roll, class_name):
            self.naam = naam          # instance variable
            self.roll = roll
            self.class_name = class_name
            self.subjects = []
            self.marks = {}

        # Method (ফাংশন)
        def add_subject(self, subject):
            self.subjects.append(subject)
            print(f"✅ {subject} যোগ করা হয়েছে!")

        def add_marks(self, subject, marks):
            if subject in self.subjects:
                self.marks[subject] = marks
                print(f"✅ {subject} এ {marks} মার্কস যোগ হয়েছে!")
            else:
                print(f"❌ {subject} বিষয়টি নেই!")

        def get_average(self):
            if self.marks:
                return sum(self.marks.values()) / len(self.marks)
            return 0

        def show_info(self):
            print("\n" + "=" * 40)
            print(f"নাম: {self.naam}")
            print(f"রোল: {self.roll}")
            print(f"ক্লাস: {self.class_name}")
            print(f"বিষয়: {', '.join(self.subjects)}")
            print(f"মার্কস: {self.marks}")
            print(f"গড়: {self.get_average():.2f}")
            print("=" * 40)

    # Object তৈরি
    student1 = Student("আহমেদ", 101, "দশম")
    student1.add_subject("বাংলা")
    student1.add_subject("ইংরেজি")
    student1.add_subject("গণিত")
    student1.add_marks("বাংলা", 85)
    student1.add_marks("ইংরেজি", 78)
    student1.add_marks("গণিত", 92)
    student1.show_info()

    # ============================================
    # Class Variables vs Instance Variables
    # ============================================

    class BankAccount:
        """ব্যাংক অ্যাকাউন্ট class"""

        # Class variable (সব object এ শেয়ার)
        bank_name = "বাংলাদেশ ব্যাংক"
        interest_rate = 0.05  # 5%
        total_accounts = 0

        def __init__(self, holder_name, initial_balance=0):
            # Instance variables (প্রতিটি object এ আলাদা)
            self.holder_name = holder_name
            self.balance = initial_balance
            self.account_number = f"ACC{BankAccount.total_accounts + 1:04d}"
            BankAccount.total_accounts += 1

        def deposit(self, amount):
            if amount > 0:
                self.balance += amount
                print(f"✅ {amount} টাকা জমা হয়েছে!")
                print(f"   বর্তমান ব্যালেন্স: {self.balance} টাকা")
            else:
                print("❌ অবৈধ পরিমাণ!")

        def withdraw(self, amount):
            if amount > self.balance:
                print("❌ পর্যাপ্ত ব্যালেন্স নেই!")
            elif amount <= 0:
                print("❌ অবৈধ পরিমাণ!")
            else:
                self.balance -= amount
                print(f"✅ {amount} টাকা উত্তোলন হয়েছে!")
                print(f"   বর্তমান ব্যালেন্স: {self.balance} টাকা")

        def add_interest(self):
            interest = self.balance * BankAccount.interest_rate
            self.balance += interest
            print(f"✅ {interest:.2f} টাকা সুদ যোগ হয়েছে!")

        def show_details(self):
            print("\n" + "-" * 35)
            print(f"ব্যাংক: {BankAccount.bank_name}")
            print(f"অ্যাকাউন্ট নম্বর: {self.account_number}")
            print(f"নাম: {self.holder_name}")
            print(f"ব্যালেন্স: {self.balance} টাকা")
            print("-" * 35)

    # ব্যবহার
    acc1 = BankAccount("করিম হোসেন", 10000)
    acc2 = BankAccount("রহিম উদ্দিন", 5000)

    acc1.deposit(5000)
    acc1.withdraw(3000)
    acc1.add_interest()
    acc1.show_details()

    acc2.show_details()

    print(f"\nমোট অ্যাকাউন্ট: {BankAccount.total_accounts}")

    # ============================================
    # Encapsulation (ডেটা লুকানো)
    # ============================================

    class SecureAccount:
        def __init__(self, holder, balance, pin):
            self.holder = holder
            self._balance = balance      # protected (convention)
            self.__pin = pin             # private (name mangling)

        def check_balance(self, pin):
            if pin == self.__pin:
                return self._balance
            else:
                return "❌ ভুল PIN!"

        def change_pin(self, old_pin, new_pin):
            if old_pin == self.__pin:
                self.__pin = new_pin
                return "✅ PIN পরিবর্তন হয়েছে!"
            else:
                return "❌ ভুল PIN!"

    account = SecureAccount("করিম", 50000, "1234")
    print(account.check_balance("1234"))  # 50000
    print(account.check_balance("0000"))  # ভুল PIN!
    # print(account.__pin)  # Error! private variable

### সপ্তাহ ২৯-৩২: Inheritance ও Polymorphism

Python

    # ============================================
    # Inheritance (উত্তরাধিকার)
    # ============================================

    # Parent/Base Class
    class Animal:
        def __init__(self, naam, boyos):
            self.naam = naam
            self.boyos = boyos

        def speak(self):
            print("প্রাণী কিছু বলছে...")

        def info(self):
            print(f"নাম: {self.naam}, বয়স: {self.boyos} বছর")

    # Child Classes
    class Dog(Animal):
        def __init__(self, naam, boyos, breed):
            super().__init__(naam, boyos)  # Parent constructor call
            self.breed = breed

        def speak(self):  # Method overriding
            print(f"{self.naam} বলছে: ঘেউ ঘেউ! 🐕")

        def fetch(self):
            print(f"{self.naam} বল আনছে!")

    class Cat(Animal):
        def __init__(self, naam, boyos, color):
            super().__init__(naam, boyos)
            self.color = color

        def speak(self):
            print(f"{self.naam} বলছে: মিয়াউ! 🐱")

        def climb(self):
            print(f"{self.naam} গাছে উঠছে!")

    class Bird(Animal):
        def __init__(self, naam, boyos, can_fly=True):
            super().__init__(naam, boyos)
            self.can_fly = can_fly

        def speak(self):
            print(f"{self.naam} বলছে: কিচির মিচির! 🐦")

        def fly(self):
            if self.can_fly:
                print(f"{self.naam} উড়ছে!")
            else:
                print(f"{self.naam} উড়তে পারে না!")

    # ব্যবহার
    tommy = Dog("টমি", 3, "জার্মান শেফার্ড")
    tommy.info()
    tommy.speak()
    tommy.fetch()

    print()

    minu = Cat("মিনু", 2, "সাদা")
    minu.info()
    minu.speak()
    minu.climb()

    print()

    # ============================================
    # Polymorphism (বহুরূপিতা)
    # ============================================

    def animal_sound(animal):
        """যেকোনো প্রাণীর ডাক"""
        animal.speak()

    animals = [
        Dog("টমি", 3, "জার্মান শেফার্ড"),
        Cat("মিনু", 2, "সাদা"),
        Bird("টিয়া", 1)
    ]

    print("সব প্রাণীর ডাক:")
    for animal in animals:
        animal_sound(animal)

    # ============================================
    # Multiple Inheritance
    # ============================================

    class Father:
        def skills(self):
            print("ব্যবসা করতে পারি")

    class Mother:
        def skills(self):
            print("রান্না করতে পারি")

        def art(self):
            print("ছবি আঁকতে পারি")

    class Child(Father, Mother):
        def skills(self):
            super().skills()  # Father's skills
            print("প্রোগ্রামিং করতে পারি")

        def all_skills(self):
            Father.skills(self)
            Mother.skills(self)
            Mother.art(self)
            print("প্রোগ্রামিং করতে পারি")

    child = Child()
    print("সন্তানের সব দক্ষতা:")
    child.all_skills()

    # ============================================
    # Abstract Class (ABC)
    # ============================================

    from abc import ABC, abstractmethod

    class Shape(ABC):
        """Abstract base class for shapes"""

        @abstractmethod
        def area(self):
            """ক্ষেত্রফল বের করতে হবে"""
            pass

        @abstractmethod
        def perimeter(self):
            """পরিধি বের করতে হবে"""
            pass

        def description(self):
            return "এটি একটি আকৃতি"

    class Rectangle(Shape):
        def __init__(self, length, width):
            self.length = length
            self.width = width

        def area(self):
            return self.length * self.width

        def perimeter(self):
            return 2 * (self.length + self.width)

    class Circle(Shape):
        def __init__(self, radius):
            self.radius = radius

        def area(self):
            import math
            return math.pi * self.radius ** 2

        def perimeter(self):
            import math
            return 2 * math.pi * self.radius

    # ব্যবহার
    shapes = [
        Rectangle(10, 5),
        Circle(7)
    ]

    for shape in shapes:
        print(f"\n{shape.__class__.__name__}:")
        print(f"  ক্ষেত্রফল: {shape.area():.2f}")
        print(f"  পরিধি: {shape.perimeter():.2f}")

    # ============================================
    # Magic/Dunder Methods
    # ============================================

    class Book:
        def __init__(self, title, author, pages):
            self.title = title
            self.author = author
            self.pages = pages

        def __str__(self):
            """print() করলে যা দেখাবে"""
            return f"'{self.title}' by {self.author}"

        def __repr__(self):
            """debugging এ যা দেখাবে"""
            return f"Book('{self.title}', '{self.author}', {self.pages})"

        def __len__(self):
            """len() করলে যা return করবে"""
            return self.pages

        def __eq__(self, other):
            """== দিয়ে compare করলে"""
            return self.title == other.title and self.author == other.author

        def __lt__(self, other):
            """< দিয়ে compare করলে"""
            return self.pages < other.pages

        def __add__(self, other):
            """+ দিয়ে যোগ করলে"""
            return self.pages + other.pages

    book1 = Book("পথের পাঁচালী", "বিভূতিভূষণ", 300)
    book2 = Book("দেবদাস", "শরৎচন্দ্র", 250)

    print(book1)                    # 'পথের পাঁচালী' by বিভূতিভূষণ
    print(f"পৃষ্ঠা: {len(book1)}")   # 300
    print(f"সমান?: {book1 == book2}") # False
    print(f"ছোট?: {book1 < book2}")   # False (300 < 250)
    print(f"মোট পৃষ্ঠা: {book1 + book2}") # 550

---

## 🎯 Phase 5: Advanced Python (মাস ৭-৮)

### সপ্তাহ ৩৩-৩৬: File Handling ও Exception

Python

    # ============================================
    # File Reading
    # ============================================

    # পদ্ধতি ১: সম্পূর্ণ ফাইল পড়া
    with open("example.txt", "r", encoding="utf-8") as file:
        content = file.read()
        print(content)

    # পদ্ধতি ২: লাইন বাই লাইন পড়া
    with open("example.txt", "r", encoding="utf-8") as file:
        for line_number, line in enumerate(file, 1):
            print(f"{line_number}: {line.strip()}")

    # পদ্ধতি ৩: সব লাইন list এ
    with open("example.txt", "r", encoding="utf-8") as file:
        lines = file.readlines()
        print(lines)

    # ============================================
    # File Writing
    # ============================================

    # নতুন ফাইল তৈরি/Overwrite
    with open("output.txt", "w", encoding="utf-8") as file:
        file.write("প্রথম লাইন\n")
        file.write("দ্বিতীয় লাইন\n")

    # Append (যোগ করা)
    with open("output.txt", "a", encoding="utf-8") as file:
        file.write("তৃতীয় লাইন\n")

    # Multiple lines
    lines = ["লাইন ১\n", "লাইন ২\n", "লাইন ৩\n"]
    with open("output.txt", "w", encoding="utf-8") as file:
        file.writelines(lines)

    # ============================================
    # JSON File Handling
    # ============================================

    import json

    # Dictionary to JSON file
    data = {
        "naam": "আহমেদ",
        "boyos": 25,
        "skills": ["Python", "JavaScript", "SQL"]
    }

    with open("data.json", "w", encoding="utf-8") as file:
        json.dump(data, file, ensure_ascii=False, indent=4)

    # JSON file to Dictionary
    with open("data.json", "r", encoding="utf-8") as file:
        loaded_data = json.load(file)
        print(loaded_data)

    # ============================================
    # CSV File Handling
    # ============================================

    import csv

    # CSV লেখা
    students = [
        ["নাম", "রোল", "মার্কস"],
        ["আহমেদ", 101, 85],
        ["করিম", 102, 92],
        ["রহিম", 103, 78]
    ]

    with open("students.csv", "w", newline="", encoding="utf-8") as file:
        writer = csv.writer(file)
        writer.writerows(students)

    # CSV পড়া
    with open("students.csv", "r", encoding="utf-8") as file:
        reader = csv.reader(file)
        for row in reader:
            print(row)

    # DictReader/DictWriter
    with open("students.csv", "r", encoding="utf-8") as file:
        reader = csv.DictReader(file)
        for row in reader:
            print(f"{row['নাম']}: {row['মার্কস']}")

    # ============================================
    # Exception Handling
    # ============================================

    # try-except
    try:
        num = int(input("একটি সংখ্যা দিন: "))
        result = 100 / num
        print(f"ফলাফল: {result}")
    except ValueError:
        print("❌ অনুগ্রহ করে সংখ্যা দিন!")
    except ZeroDivisionError:
        print("❌ শূন্য দিয়ে ভাগ করা যায় না!")
    except Exception as e:
        print(f"❌ অজানা ত্রুটি: {e}")
    else:
        print("✅ কোনো ত্রুটি হয়নি!")
    finally:
        print("এটি সবসময় চলবে!")

    # ============================================
    # Custom Exception
    # ============================================

    class InsufficientBalanceError(Exception):
        """ব্যালেন্স কম থাকলে এই error"""
        def __init__(self, balance, amount):
            self.balance = balance
            self.amount = amount
            self.message = f"ব্যালেন্স {balance} টাকা, {amount} টাকা উত্তোলন সম্ভব নয়!"
            super().__init__(self.message)

    class NegativeAmountError(Exception):
        """নেগেটিভ amount দিলে এই error"""
        pass

    def withdraw(balance, amount):
        if amount < 0:
            raise NegativeAmountError("Amount নেগেটিভ হতে পারে না!")
        if amount > balance:
            raise InsufficientBalanceError(balance, amount)
        return balance - amount

    try:
        new_balance = withdraw(5000, 7000)
    except InsufficientBalanceError as e:
        print(f"❌ {e}")
    except NegativeAmountError as e:
        print(f"❌ {e}")

### সপ্তাহ ৩৭-৪০: Modules ও Packages

Python

    # ============================================
    # Module তৈরি করা (my_math.py)
    # ============================================

    # my_math.py ফাইলে:
    """
    কাস্টম গণিত মডিউল
    """

    PI = 3.14159

    def add(a, b):
        return a + b

    def subtract(a, b):
        return a - b

    def multiply(a, b):
        return a * b

    def divide(a, b):
        if b == 0:
            raise ValueError("শূন্য দিয়ে ভাগ করা যায় না!")
        return a / b

    def circle_area(radius):
        return PI * radius ** 2

    class Calculator:
        def __init__(self):
            self.result = 0

        def add(self, num):
            self.result += num
            return self

        def subtract(self, num):
            self.result -= num
            return self

        def reset(self):
            self.result = 0
            return self

    # ============================================
    # Module Import করা
    # ============================================

    # সম্পূর্ণ module import
    import my_math
    print(my_math.add(5, 3))
    print(my_math.PI)

    # নির্দিষ্ট function import
    from my_math import add, subtract, PI
    print(add(5, 3))

    # alias দিয়ে import
    import my_math as mm
    print(mm.multiply(4, 5))

    # সব কিছু import (avoid করুন)
    from my_math import *

    # ============================================
    # Built-in Modules
    # ============================================

    # os module
    import os

    print(f"বর্তমান directory: {os.getcwd()}")
    print(f"ফাইল আছে?: {os.path.exists('example.txt')}")

    # sys module
    import sys
    print(f"Python version: {sys.version}")
    print(f"Arguments: {sys.argv}")

    # datetime module
    from datetime import datetime, timedelta

    now = datetime.now()
    print(f"এখন: {now.strftime('%Y-%m-%d %H:%M:%S')}")

    tomorrow = now + timedelta(days=1)
    print(f"আগামীকাল: {tomorrow.strftime('%Y-%m-%d')}")

    # random module
    import random

    print(f"Random number: {random.randint(1, 100)}")
    print(f"Random choice: {random.choice(['আম', 'কাঁঠাল', 'লিচু'])}")

    numbers = [1, 2, 3, 4, 5]
    random.shuffle(numbers)
    print(f"Shuffled: {numbers}")

    # math module
    import math

    print(f"π = {math.pi}")
    print(f"√16 = {math.sqrt(16)}")
    print(f"2³ = {math.pow(2, 3)}")
    print(f"log₁₀(100) = {math.log10(100)}")

    # ============================================
    # Package Structure
    # ============================================

    """
    my_package/
    │
    ├── __init__.py
    ├── module1.py
    ├── module2.py
    │
    └── sub_package/
        ├── __init__.py
        └── module3.py
    """

    # __init__.py ফাইলে:
    from .module1 import function1
    from .module2 import function2

    # ব্যবহার:
    from my_package import function1, function2
    from my_package.sub_package import module3

    # ============================================
    # pip দিয়ে package install
    # ============================================

    """
    Terminal commands:

    # Package install
    pip install requests
    pip install numpy pandas matplotlib

    # নির্দিষ্ট version
    pip install requests==2.28.0

    # requirements.txt থেকে install
    pip install -r requirements.txt

    # Installed packages দেখা
    pip list

    # Package uninstall
    pip uninstall requests
    """

---

## 🎯 Phase 6: AI/ML এর জন্য প্রস্তুতি (মাস ৯-১২)

### সপ্তাহ ৪১-৪৪: NumPy

Python

    # ============================================
    # NumPy Basics
    # ============================================

    import numpy as np

    # Array তৈরি
    arr1 = np.array([1, 2, 3, 4, 5])
    print(f"1D Array: {arr1}")
    print(f"Shape: {arr1.shape}")
    print(f"Type: {arr1.dtype}")

    # 2D Array (Matrix)
    arr2d = np.array([
        [1, 2, 3],
        [4, 5, 6],
        [7, 8, 9]
    ])
    print(f"\n2D Array:\n{arr2d}")

    # বিশেষ arrays
    zeros = np.zeros((3, 3))        # সব 0
    ones = np.ones((2, 4))          # সব 1
    identity = np.eye(3)            # Identity matrix
    random_arr = np.random.rand(3, 3)  # Random 0-1

    print(f"\nZeros:\n{zeros}")
    print(f"\nRandom:\n{random_arr}")

    # ============================================
    # Array Operations
    # ============================================

    a = np.array([1, 2, 3, 4])
    b = np.array([5, 6, 7, 8])

    print(f"যোগ: {a + b}")
    print(f"গুণ: {a * b}")
    print(f"বর্গ: {a ** 2}")
    print(f"বর্গমূল: {np.sqrt(a)}")

    # ============================================
    # Statistical Operations
    # ============================================

    data = np.array([85, 92, 78, 95, 88, 76, 91, 83])

    print(f"\nStatistics:")
    print(f"Mean: {np.mean(data):.2f}")
    print(f"Median: {np.median(data):.2f}")
    print(f"Std: {np.std(data):.2f}")
    print(f"Max: {np.max(data)}")
    print(f"Min: {np.min(data)}")

    # ============================================
    # Matrix Operations (ML এ গুরুত্বপূর্ণ!)
    # ============================================

    A = np.array([[1, 2], [3, 4]])
    B = np.array([[5, 6], [7, 8]])

    print(f"\nMatrix A:\n{A}")
    print(f"Matrix B:\n{B}")
    print(f"Matrix Multiplication:\n{np.dot(A, B)}")
    print(f"Transpose:\n{A.T}")
    print(f"Inverse:\n{np.linalg.inv(A)}")

### সপ্তাহ ৪৫-৪৮: Pandas

Python

    # ============================================
    # Pandas Basics
    # ============================================

    import pandas as pd

    # Series (1D)
    marks = pd.Series([85, 92, 78, 95],
                      index=['বাংলা', 'ইংরেজি', 'গণিত', 'বিজ্ঞান'])
    print("Series:")
    print(marks)

    # DataFrame (2D)
    data = {
        'নাম': ['আহমেদ', 'করিম', 'রহিম', 'জামাল'],
        'বয়স': [22, 25, 21, 23],
        'শহর': ['ঢাকা', 'চট্টগ্রাম', 'রাজশাহী', 'খুলনা'],
        'মার্কস': [85, 92, 78, 88]
    }
    df = pd.DataFrame(data)
    print("\nDataFrame:")
    print(df)

    # ============================================
    # Data Reading/Writing
    # ============================================

    # CSV পড়া
    # df = pd.read_csv('students.csv')

    # Excel পড়া
    # df = pd.read_excel('students.xlsx')

    # CSV এ সংরক্ষণ
    # df.to_csv('output.csv', index=False)

    # ============================================
    # Data Exploration
    # ============================================

    print(f"\nShape: {df.shape}")
    print(f"\nColumns: {df.columns.tolist()}")
    print(f"\nInfo:")
    print(df.info())
    print(f"\nDescribe:")
    print(df.describe())
    print(f"\nFirst 2 rows:")
    print(df.head(2))

    # ============================================
    # Data Selection
    # ============================================

    # Column select
    print(df['নাম'])
    print(df[['নাম', 'মার্কস']])

    # Row select
    print(df.loc[0])          # by label
    print(df.iloc[0:2])       # by index

    # Conditional select
    print(df[df['মার্কস'] > 80])

    # ============================================
    # Data Manipulation
    # ============================================

    # নতুন column যোগ
    df['গ্রেড'] = df['মার্কস'].apply(
        lambda x: 'A+' if x >= 90 else 'A' if x >= 80 else 'B'
    )
    print(df)

    # Group by
    print(df.groupby('গ্রেড')['মার্কস'].mean())

    # Sorting
    print(df.sort_values('মার্কস', ascending=False))

### সপ্তাহ ৪৯-৫২: Matplotlib ও Seaborn

Python

    # ============================================
    # Matplotlib Basics
    # ============================================

    import matplotlib.pyplot as plt
    import numpy as np

    # Line Plot
    x = np.linspace(0, 10, 100)
    y = np.sin(x)

    plt.figure(figsize=(10, 6))
    plt.plot(x, y, label='sin(x)', color='blue')
    plt.plot(x, np.cos(x), label='cos(x)', color='red')
    plt.xlabel('X অক্ষ')
    plt.ylabel('Y অক্ষ')
    plt.title('Sine ও Cosine গ্রাফ')
    plt.legend()
    plt.grid(True)
    plt.savefig('plot.png')
    plt.show()

    # Bar Chart
    subjects = ['বাংলা', 'ইংরেজি', 'গণিত', 'বিজ্ঞান']
    marks = [85, 92, 78, 88]

    plt.figure(figsize=(8, 6))
    plt.bar(subjects, marks, color=['red', 'green', 'blue', 'orange'])
    plt.xlabel('বিষয়')
    plt.ylabel('মার্কস')
    plt.title('বিষয়ভিত্তিক মার্কস')
    plt.show()

    # Pie Chart
    plt.figure(figsize=(8, 8))
    plt.pie(marks, labels=subjects, autopct='%1.1f%%', startangle=90)
    plt.title('মার্কস বিতরণ')
    plt.show()

    # ============================================
    # Seaborn (Advanced Visualization)
    # ============================================

    import seaborn as sns

    # Sample data
    tips = sns.load_dataset('tips')

    # Distribution Plot
    plt.figure(figsize=(10, 6))
    sns.histplot(tips['total_bill'], kde=True)
    plt.title('Total Bill Distribution')
    plt.show()

    # Scatter Plot with Regression
    plt.figure(figsize=(10, 6))
    sns.regplot(x='total_bill', y='tip', data=tips)
    plt.title('Bill vs Tip')
    plt.show()

    # Heatmap (Correlation)
    plt.figure(figsize=(8, 6))
    correlation = tips.corr()
    sns.heatmap(correlation, annot=True, cmap='coolwarm')
    plt.title('Correlation Heatmap')
    plt.show()

---

## 🎯 Machine Learning শুরু করুন

### Scikit-learn দিয়ে প্রথম ML Model

Python

    # ============================================
    # ML Model তৈরি (Classification)
    # ============================================

    from sklearn.datasets import load_iris
    from sklearn.model_selection import train_test_split
    from sklearn.ensemble import RandomForestClassifier
    from sklearn.metrics import accuracy_score, classification_report

    # Data load
    iris = load_iris()
    X = iris.data      # Features
    y = iris.target    # Labels

    # Train-Test Split
    X_train, X_test, y_train, y_test = train_test_split(
        X, y, test_size=0.2, random_state=42
    )

    # Model তৈরি ও train
    model = RandomForestClassifier(n_estimators=100, random_state=42)
    model.fit(X_train, y_train)

    # Prediction
    y_pred = model.predict(X_test)

    # Evaluation
    accuracy = accuracy_score(y_test, y_pred)
    print(f"Accuracy: {accuracy * 100:.2f}%")
    print("\nClassification Report:")
    print(classification_report(y_test, y_pred, target_names=iris.target_names))

---

## 📚 Learning Resources

### বাংলা Resources:

text

    📺 YouTube Channels:
       - Anisul Islam
       - Stack Learner
       - Learn with Sumit

    📖 Books:
       - হাতেখড়ি পাইথন (Tamim Shahriar)

### English Resources:

text

    🌐 Websites:
       - Kaggle.com (ML practice)
       - LeetCode.com (Problem solving)
       - Coursera.org (Courses)

    📺 YouTube:
       - Sentdex
       - Corey Schafer
       - Tech With Tim

---

## 🗓️ ১২ মাসের Summary Roadmap

text

    ┌─────────────────────────────────────────────────────────────┐
    │                    PYTHON MASTERY ROADMAP                    │
    ├─────────────────────────────────────────────────────────────┤
    │                                                              │
    │  Month 1-2:   Python Basics                                  │
    │               ├── Variables, Data Types                      │
    │               ├── Operators, Strings                         │
    │               └── Input/Output                               │
    │                                                              │
    │  Month 3-4:   Control Flow & Data Structures                 │
    │               ├── if-elif-else, Loops                        │
    │               ├── Functions, Lambda                          │
    │               ├── List, Tuple, Set                           │
    │               └── Dictionary                                 │
    │                                                              │
    │  Month 5-6:   OOP & Advanced Concepts                        │
    │               ├── Classes, Objects                           │
    │               ├── Inheritance, Polymorphism                  │
    │               ├── File Handling                              │
    │               └── Exception Handling                         │
    │                                                              │
    │  Month 7-8:   Modules & Advanced Topics                      │
    │               ├── Modules, Packages                          │
    │               ├── Regular Expressions                        │
    │               ├── Decorators, Generators                     │
    │               └── Multi-threading                            │
    │                                                              │
    │  Month 9-10:  Data Science Libraries                         │
    │               ├── NumPy                                      │
    │               ├── Pandas                                     │
    │               └── Matplotlib, Seaborn                        │
    │                                                              │
    │  Month 11-12: Machine Learning                               │
    │               ├── Scikit-learn                               │
    │               ├── TensorFlow/PyTorch basics                  │
    │               └── Real Projects                              │
    │                                                              │
    └─────────────────────────────────────────────────────────────┘

---

## ✅ Daily Practice Routine

text

    সকাল (1 ঘণ্টা):
    ├── নতুন concept শেখা
    └── Documentation পড়া

    বিকাল (2 ঘণ্টা):
    ├── Code practice
    ├── Project work
    └── Problem solving

    রাত (1 ঘণ্টা):
    ├── Review
    ├── Notes তৈরি
    └── পরের দিনের plan

---

## 🎯 Final Tips

text

    ✅ প্রতিদিন minimum 3-4 ঘণ্টা practice করুন
    ✅ প্রতিটি concept hands-on করুন
    ✅ ছোট ছোট project করুন
    ✅ GitHub এ code share করুন
    ✅ Community তে যুক্ত থাকুন
    ✅ ভুল করতে ভয় পাবেন না
    ✅ Consistency সবচেয়ে গুরুত্বপূর্ণ!

---

**শুভকামনা! আপনি অবশ্যই একজন সফল AI/ML Engineer হতে পারবেন! 🚀**
