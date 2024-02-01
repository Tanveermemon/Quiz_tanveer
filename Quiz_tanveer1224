students_data = [
    ["ali", "akber1", "85", "45", "50"],
    ["Kamran", "akber2", "95", "55", "60"],
    ["Noman", "akber3", "75", "65", "70"],
    ["Waqas", "akber4", "65", "75", "80"],
    ["Azahr", "akber5", "55", "85", "90"],
    ["Afzal", "akber6", "45", "95", "100"],
]
total_marks = 300
passing_marks = 50

# Writing existing students_data to a file
with open("students_info.txt", "w") as file:
    file.write("Existing Students Data:\n")
    for data in students_data:
        name, fname, maths_marks, physics_marks, sindhi_marks = data
        total_marks_obtained = sum(map(int, [maths_marks, physics_marks, sindhi_marks]))

        if all(int(mark) >= passing_marks for mark in [maths_marks, physics_marks, sindhi_marks]):
            result = "passed"
        else:
            result = "failed"
        file.write(f"{name} son of {fname} has {result} with total numbers {total_marks_obtained}\n")

students_strengths = int(input("How many Students? "))
students_list = []

for _ in range(students_strengths):
    std_data = dict()
    name = input("Enter name: ")
    fname = input("Enter father name: ")
    age = int(input("Enter the age of students: "))
    subjects_marks = {
        "Math": int(input("Enter marks for Math: ")),
        "Physics": int(input("Enter marks for Physics: ")),
        "Sindhi": int(input("Enter marks for Sindhi: "))
    }
    std_data["name"] = name
    std_data["fname"] = fname
    std_data["age"] = age
    std_data["subjects_marks"] = subjects_marks
    students_list.append(std_data)

# Writing new students_list to the same file
with open("students_info.txt", "a") as file:
    file.write("\nNew Students Data:\n")
    for student in students_list:
        file.write(f"{student['name']} son of {student['fname']} - Age: {student['age']}\n")
        for subject, marks in student["subjects_marks"].items():
            file.write(f"{subject}: {marks}\n")
        file.write("\n")



students_data = [
    ["ali", "akber1", "85", "45", "50"],
    ["Kamran", "akber2", "95", "55", "60"],
    ["Noman", "akber3", "75", "65", "70"],
    ["Waqas", "akber4", "65", "75", "80"],
    ["Azahr", "akber5", "55", "85", "90"],
    ["Afzal", "akber6", "45", "95", "100"],
]
total_marks = 300
passing_marks = 50

for data in students_data:
    name = data[0]
    fname = data[1]
    maths_marks = int(data[2])
    physics_marks = int(data[3])
    sindhi_marks = int(data[4])
    total_marks_obtained = sum([maths_marks, physics_marks, sindhi_marks])

    if maths_marks >= passing_marks and physics_marks >= passing_marks and sindhi_marks >= passing_marks:
        result = "passed"
    else:
        result = "failed"
    # print(name, "son of", fname, "has", result, "with total numbers", total_marks_obtained)

students_strengths = int(input("How many Students? "))
students_list = []

for _ in range(students_strengths):
    std_data = dict()
    name = input("Enter name: ")
    fname = input("Enter father name: ")
    age = int(input("Enter the age of students: ")) 
    subjects_marks = {
        "Maths": int(input("Enter marks for Math: ")),
        "Physisc": int(input("Enter marks for Physics: ")),
        "Sindhi":int(input("Enter marks for Sindhi: "))
    }
    std_data["name"] = name
    std_data["fname"] = fname
    std_data["age"] = age
    std_data["subjects_marks"] = subjects_marks
    students_list.append(std_data)

print(students_list)
