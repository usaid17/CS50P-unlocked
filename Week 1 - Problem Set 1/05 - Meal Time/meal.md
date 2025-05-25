def main():

    time = input("What time is it? ").strip()

    current_time = convert(time)

  

    if 7.0 <= current_time <= 8.0 :

        print ("breakfast time")

  

    elif 12.0 <= current_time <= 13.0 :

        print ("lunch time")

  

    elif 18.0 <= current_time <= 19.0 :

        print ("dinner time")

  
  

def convert(time):

    hours, minutes = time.split(":") # Split string into hours and minutes

    return int(hours) + (int(minutes) / 60) # Convert minutes to fraction of an hour

  
  

if __name__ == "__main__":

    main()