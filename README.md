# MidtermQuestion5
Problem 5

def dict_invert(d):
inverse = {}
for elm in d.keys():
  if d[elm] in inverse:
    inverse[d[elm]].append(elm)
  else:
    invers[d[elm]] = [elm]
for val in inverse.values():
  val.sort()
return inverse
