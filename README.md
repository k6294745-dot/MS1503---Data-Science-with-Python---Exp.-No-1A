# Employee Payroll Calculation

# Get employee details
name = input("Enter Employee Name: ")

emp_id = input("Enter Employee ID: ")

basic = float(input("Enter Basic Pay: "))

# Calculate allowances
hra = 0.15 * basic

da = 0.10 * basic

# Calculate gross salary
gross = basic + hra + da

# Calculate tax
tax = 0.08 * gross

# Calculate net salary
net = gross - tax

# Display employee salary report
print("\n--- Employee Salary Report ---")

print(f"Employee Name: {name}")

print(f"Employee ID: {emp_id}")

print(f"Basic Pay: {basic}")

print(f"HRA: {hra}")

print(f"DA: {da}")

print(f"Gross Salary: {gross}")

print(f"Tax Deducted: {tax}")

print(f"Net Salary: {net}")
