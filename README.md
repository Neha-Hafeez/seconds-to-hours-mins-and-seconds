def coversion(millisec):
    sec = millisec/1000
    min=sec/60
    hour=min/60
    print('milli sec to sec = ',sec,'\n')
    print('milli sec to min = ', min,'\n')
    print('milli sec to hour = ', hour,'\n')
def main():
    milisecond= int(input('time in milli second = '))
    coversion(milisecond)
if __name__ == "__main__":
    main()
