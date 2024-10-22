# SLUE

**SLUE** (Smart Plant Watering System) is an automatic watering solution designed to keep your plants healthy even when you're away. By measuring soil moisture and plant nutrients, SLUE waters your plants only when necessary, ensuring optimal care.

## Inspiration

The idea for **SLUE** came about after a family trip to Paris. My mom, an avid gardener, was worried about her plants while we were away. Unfortunately, her concerns were justified—many of the plants wilted due to lack of water. This inspired me to create a simple device that could take care of watering plants when we're not around, giving plant lovers peace of mind during their travels.

## What It Does

**SLUE** automates the watering process by using a soil moisture sensor to detect when a plant needs water. It then activates a water pump to deliver just the right amount of water. Additionally, it tracks plant nutrients and moisture levels, sending notifications through an app when the plant is watered.

## How We Built It

**SLUE** was developed using:

- **Arduino** to collect data from a soil moisture sensor.
- A **water pump** to deliver water based on sensor data.
- **Flutter** for building a mobile app that sends notifications when the plant is being watered.
- **AskSensors** to upload and extract real-time data from the sensor.

## Challenges We Faced

- Initially, we struggled with getting the motor to start due to improper Arduino configuration.
- We also faced difficulties in sending data from the soil moisture sensor to Firebase, which led us to switch to **AskSensors** for a more seamless integration.

## Accomplishments We're Proud Of

We successfully implemented a fully functional water pump system that responds to real-time sensor data. Additionally, we were able to retrieve and display soil moisture data in our mobile app through **AskSensors**.

## What We Learned

We gained valuable experience working with **Arduino** and **AskSensors**, learning how to integrate hardware with cloud platforms and mobile apps. We also improved our troubleshooting skills, particularly when dealing with hardware and connectivity issues.

## What's Next for SLUE

We plan to:

- Develop a professional-grade mobile app for SLUE with improved features.
- Transition from **AskSensors** to **Firebase** for enhanced data security and scalability.
- Display real-time soil moisture and nutrient levels within the app.
- Create a web-based interface for users to monitor their plants from any device.

## Hackathon Experience

**SLUE** was developed at a 24-hour hackathon called **Expo Hacks II**. Despite the time constraints, our team managed to complete the project and submit it successfully. We are proud to announce that **SLUE won 3rd place** in the competition! You can learn more about the hackathon at [Expo Hacks II](https://expo-hacks-ii.devpost.com/).



## How to Use SLUE

### Prerequisites

To set up SLUE, ensure you have the following components:

- Arduino board
- Soil moisture sensor
- Water pump
- Flutter for mobile app development
- AskSensors account for data integration

### Installing

1. **Clone the repository:**


git clone (`https://github.com/1300Sarthak/Slue.git`) 

2. **Set up Arduino:**

- Connect the soil moisture sensor and water pump to your Arduino board.
- Upload the Arduino code provided in the repository.

3. **Set up AskSensors:**

- Create an account and configure your sensor to send data to the AskSensors platform.
- Link the AskSensors data to the Flutter app using the provided API.

4. **Run the App:**

- Use the provided Flutter code to build and run the mobile app.
- Monitor your plant’s watering status and receive notifications when watering occurs.



### Testing the System
Once set up, you can test the system by:

- Checking soil moisture levels using the sensor.
- Monitoring the water pump as it delivers water based on sensor data.
- Receiving real-time notifications through the mobile app.


### Built With
- Arduino for hardware control
- Flutter for mobile app development
- AskSensors for cloud data integration


### Authors
* **Sarthak Sethi** - [GitHub](https://github.com/1300Sarthak)

