import time

def convert(sec):
    minits = sec // 60
    second = sec % 60
    hour = minits // 60
    min = minits % 60
    return f"{int(hour)}:{int(min)}:{int(second)}"

start_signal = input('Push "START" to Start')
start_time = time.time()

stop_signal = input('Push "STOP" to Stop')
stop_time = time.time()

stop_time - start_time = time.time()

print('Push "START" to Start')
print('Push "STOP" to Stop')
print('Push "RESET" to reset')
