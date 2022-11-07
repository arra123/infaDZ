runners=[]
with open('run_of_60_m.txt', 'r') as file:
 for line in file:
  line = line.rstrip('\n')
  name, gender, class, time = line.split()
  runner = {
  'surname': name
  'gender': gender
  'class': class
  'time'= time
}
  class = int(class)
  time = float(time)

#определение оценки
 if gender == 'G':
  if class == 7:
   if time <= 9.8:
    print(surname,5)
   elif time <= 10.6:
    print(surname,4)
   elif time <= 11.4:
    print(surname,3)
   else:
    print(surname,2)
  elif class == 6:
   if time <= 10.3:
    print(surname,5)
   elif time <= 10.6:
    print(surname,4)
   elif time <= 11.2:
    print(surname,3)
   else:
    print(surname,2)
 if gender == 'B':
  if class == 7:
   if time <= 9.4:
    print(surname,5)
   elif time <= 10.2:
    print(surname,4)
   elif time <= 11.0:
    print(surname,3)
   else:
    print(surname,2)
  elif class == 6:
   if time <= 9.9:
    print(surname,5)
   elif time <= 10.4:
    print(surname,4)
   elif time <= 11.1:
    print(surname,3)
   else:
    print(surname,2)

#даюбавление оценки
runner['mark'] = str(mark)
runners.append(runner)
if gender == 'G':
 if float(bestG['time']) > time:
  bestG = runner
 else:
  if float(bestB['time'] > time:
   bestB = runner
with open('run_of_60_m.txt', 'r') as file:
 for runner in runnersMarked:
  file.write(" ".join([runner["name"],
                runner["class"],
                str(runner["time"]),
                str(runner["mark"])+"\n"]))

 
      
