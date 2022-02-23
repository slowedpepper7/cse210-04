# cse210-04

# JUST SUGGESTION..............

def play_greed():
    score = [random.randint(1, 6)]
    for _ in range(5)
    count = [score.count(i)]
    for i in range(1, 6+1)
    points = 0

    if count[0] < 3:
        points += 100 * count[0]
    elif count[0] == 3: 
      points += 1000

    if count[4] < 3:
        points+= 50 * count[4]
    elif count[4] == 3: 
      points += 500

    if count[1] == 3: points += 200
    elif count[2] == 3 : points += 300
    elif count[3] == 3 : points += 400
    elif count[5] == 3 : points += 600

    return points
