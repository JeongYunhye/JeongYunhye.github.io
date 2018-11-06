

```python
# -*- coding: utf-8 -*-
# Car Class 
class Car:
    def __init__(self, model_name):
        self.model_name = model_name
# Stop 
    def stop(self):
        # Engine Stop
        print "엔진을 정지합니다."

# Start 
    def start(self):
        # Engine Run
        print "엔진을 가동합니다."

# Run
    def run(self):
        # drive
        print "정속 운행을 합니다."

# Break
    def break_pad(self):
        # break
        print "브레이크를 밟습니다."

# Get Car name 
    def get_car_name(self):
        print self.model_name + "이(가) 달립니다."

# ElectricCar Class

# Stop 
# Motor stop

# Start 
# Motor run

# Run
# drive

# Break
# break
# batteryCharge

# HybridCar Class

# Stop 
# Engine Stop
# Motor stop

# Start 
# Engine Run

# Run
# drive

# Break
# break
# batteryCharge        
        
def main():
    print "메인함수입니다."
    normal_car_1 = Car("엔진차1")
    normal_car_1.get_car_name()
    normal_car_1.stop()
    normal_car_1.start()
    normal_car_1.run()
    normal_car_1.break_pad()

if __name__ == '__main__':
    main()
```
