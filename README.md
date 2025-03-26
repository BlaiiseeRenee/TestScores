testscores = [99,78,85,96]
total = 0

def getsum(scores):
    global total
    for x in scores:
        total += x
    return total

def getavg():
    gsum = getsum(testscores)
    return gsum/len(testscores)

def main():
    print(getavg())


main()
