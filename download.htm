# ============================================
#       ATTENDANCE MONITORING SYSTEM
# ============================================

students = []

while True:

    print("\n" + "=" * 40)
    print("   ATTENDANCE MONITORING SYSTEM")
    print("=" * 40)

    print("1. Add Student")
    print("2. Record Attendance")
    print("3. View Attendance")
    print("4. Search Student")
    print("5. Update Attendance")
    print("6. Attendance Summary")
    print("7. Exit")

    choice = input("\nEnter your choice: ")

    # ==========================================
    # 1. ADD STUDENT
    # ==========================================

    if choice == "1":

        print("\n--- ADD STUDENT ---")

        # Student ID
        while True:
            student_id = input("Enter Student ID: ").strip()

            if student_id.isdigit():
                break

            print("Invalid Student ID. Please enter numbers only.")

        # Student Name
        while True:
            student_name = input("Enter Student Name: ").strip()

            if student_name and student_name.replace(" ", "").isalpha():
                break

            print("Invalid Student Name. Please enter letters only.")

        student = {
            "id": student_id,
            "name": student_name,
            "attendance": []
        }

        students.append(student)

        print("\nStudent added successfully!")

    # ==========================================
    # 2. RECORD ATTENDANCE
    # ==========================================

    elif choice == "2":

        print("\n--- RECORD ATTENDANCE ---")

        if len(students) == 0:
            print("No students have been added yet.")
            continue

        student_id = input("Enter Student ID: ").strip()

        found = False

        for student in students:

            if student["id"] == student_id:

                while True:
                    status = input(
                        "Enter Attendance (Present/Absent): "
                    ).strip().lower()

                    if status == "present":
                        student["attendance"].append("Present")
                        print("Attendance recorded as Present.")
                        break

                    elif status == "absent":
                        student["attendance"].append("Absent")
                        print("Attendance recorded as Absent.")
                        break

                    else:
                        print(
                            "Invalid input. "
                            "Please enter Present or Absent."
                        )

                found = True
                break

        if not found:
            print("Student ID not found.")

    # ==========================================
    # 3. VIEW ATTENDANCE
    # ==========================================

    elif choice == "3":

        print("\n--- VIEW ATTENDANCE ---")

        if len(students) == 0:
            print("No students have been added yet.")
            continue

        for student in students:

            print("\nStudent ID   :", student["id"])
            print("Student Name :", student["name"])

            if len(student["attendance"]) == 0:
                print("Attendance   : No attendance recorded.")

            else:
                print("Attendance   :")

                for record in student["attendance"]:
                    print("-", record)

    # ==========================================
    # 4. SEARCH STUDENT
    # ==========================================

    elif choice == "4":

        print("\n--- SEARCH STUDENT ---")

        student_id = input("Enter Student ID: ").strip()

        found = False

        for student in students:

            if student["id"] == student_id:

                print("\nStudent Found!")
                print("Student ID   :", student["id"])
                print("Student Name :", student["name"])

                found = True
                break

        if not found:
            print("Student ID not found.")

    # ==========================================
    # 5. UPDATE ATTENDANCE
    # ==========================================

    elif choice == "5":

        print("\n--- UPDATE ATTENDANCE ---")

        student_id = input("Enter Student ID: ").strip()

        found = False

        for student in students:

            if student["id"] == student_id:

                if len(student["attendance"]) == 0:
                    print("No attendance record available.")
                    found = True
                    break

                while True:

                    status = input(
                        "Enter New Attendance "
                        "(Present/Absent): "
                    ).strip().lower()

                    if status == "present":

                        student["attendance"][-1] = "Present"
                        print("Attendance updated successfully.")
                        break

                    elif status == "absent":

                        student["attendance"][-1] = "Absent"
                        print("Attendance updated successfully.")
                        break

                    else:
                        print(
                            "Invalid input. "
                            "Please enter Present or Absent."
                        )

                found = True
                break

        if not found:
            print("Student ID not found.")

    # ==========================================
    # 6. ATTENDANCE SUMMARY
    # ==========================================

    elif choice == "6":

        print("\n--- ATTENDANCE SUMMARY ---")

        if len(students) == 0:
            print("No students have been added yet.")
            continue

        for student in students:

            total = len(student["attendance"])
            present = student["attendance"].count("Present")
            absent = student["attendance"].count("Absent")

            print("\nStudent ID   :", student["id"])
            print("Student Name :", student["name"])
            print("Total Records:", total)
            print("Present      :", present)
            print("Absent       :", absent)

            if total > 0:
                rate = (present / total) * 100
                print(f"Attendance Rate: {rate:.2f}%")
            else:
                print("Attendance Rate: No record")

    # ==========================================
    # 7. EXIT
    # ==========================================

    elif choice == "7":

        print("\nThank you for using the")
        print("Attendance Monitoring System!")

        break

    # ==========================================
    # INVALID CHOICE
    # ==========================================

    else:

        print("\nInvalid choice.")
        print("Please select a number from 1 to 7.")