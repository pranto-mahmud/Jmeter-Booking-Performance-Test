# JMeter Performance Testing – Restful Booker API

## What Has Been Done
- Created a JMeter test plan (booking.jmx)
- Implemented API chaining: Login → Create Booking → Search Booking
- Added required headers and Gaussian Random Timer
- Performed load and stress testing
- Generated HTML and Excel test reports

## Prerequisites
- Java JDK 8+
- Apache JMeter 5.6+

## How to Run the Tests
1. Open booking.jmx in Apache JMeter
2. Configure Thread Group if needed
3. Run the test
4. Generate HTML report and review results

### Screenshots & Reports
- **Load Test Results**
  
Request Summary (Load Test) <img width="1692" height="744" alt="Load requests summary" src="https://github.com/user-attachments/assets/7b594a54-65f3-44fc-809e-39d638c27785" />

Statistics (HTML Report – Load Test) <img width="1548" height="414" alt="Load statistics" src="https://github.com/user-attachments/assets/50cb0e03-06c7-4203-93f3-1c00abd05902" />


Excel Report (Load Test) <img width="1062" height="338" alt="Load test report" src="https://github.com/user-attachments/assets/60fc7efa-91a4-4654-9696-a8956500500a" />

- **Stress Test Results**
  
Request Summary (Stress Test) <img width="1536" height="684" alt="Stress requests summary" src="https://github.com/user-attachments/assets/1a5bcbed-7a70-4cd7-b9f2-c64481a364d3" />

Statistics (HTML Report – Stress Test) <img width="1553" height="417" alt="Stress statistics" src="https://github.com/user-attachments/assets/2c56b936-983d-4a18-a30e-3b694c4722bb" />

Excel Report (Stress Test) <img width="1216" height="293" alt="Stress test strategy" src="https://github.com/user-attachments/assets/e2f5323c-7d18-4f59-bece-a8698d1f5ba1" />


- Author: Syed Shahanur Mahmud Pranto
- Email: prantosm33@gmail.com

