service_schedule = {"-": 0,"Oil change" : 35, "Tire rotation" : 19, "Car wash" : 7, "Car wax": 12}
total = 0
print("Davy's auto shop services")
print('Oil change -- $35')
print('Tire rotation -- $19')
print('Car wash -- $7')
print('Car wax -- $12\n')
service1 = input('Select first service:\n')
service2 = input('Select second service:\n')
print()
print("Davy's auto shop invoice")
print()
if(service1 == "-"):
  print("Service 1: No service")
else:
  print("Service 1: %s, $%d" %(service1, service_schedule.get(service1)))
if(service2 == "-"):
  print("Service 2: No service")
else:
  print("Service 2: %s, $%d" %(service2, service_schedule.get(service2)))
total = service_schedule.get(service1) + service_schedule.get(service2)
print()
print("Total: $%d" % (total))

    
    
