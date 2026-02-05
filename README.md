# Performance Test: BlazeDemo Flight Booking
This project demonstrates end-to-end performance testing using Apache JMeter.

## 🚀 Scenarios Tested
1. **Home Page Load**: Verified landing page stability.
2. **Flight Search**: Dynamic search from Paris to Buenos Aires.
3. **Correlation**: Extracted `flight_number` using Regex to simulate a real booking flow.

## 📊 Test Configurations
- **Virtual Users:** 10
- **Ramp-up Period:** 5 seconds
- **Assertions:** Response Assertion for 200 OK and text validation.
- **Timers:** 2000ms Constant Timer to simulate human "Think Time."

## 📈 Results
- **Success Rate:** 100%
- **Average Response Time:** [Insert your average time here, e.g., 250ms]
