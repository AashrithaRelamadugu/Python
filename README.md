# Python
tasks = []

def add_task(task):
    tasks.append(task)

def remove_task(task):
    tasks.remove(task)

def view_tasks():
    for index, task in enumerate(tasks, start=1):
        print(f"{index}. {task}")

# Adding tasks
add_task(input())
add_task(input())
add_task(input())

# Viewing tasks
print("Current Tasks:")
view_tasks()

# Removing a task
remove_task("Buy groceries")

# Viewing tasks after removal
print("\nUpdated Tasks:")
view_tasks()