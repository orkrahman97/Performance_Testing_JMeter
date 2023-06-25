# Performance_Testing_JMeter

This document shows the performance test 






## Load Testing

**I was tasked with performance testing the Bangla Puzzle website as part of my internship. I used JMeter to simulate 100-200 users accessing the website at the same time. The results showed that the website was able to handle the load without any significant performance degradation. The average response time was 2.3 seconds, and for 500 people the maximum response time was 5.5 seconds. These results are well within the acceptable range and indicate that the website is capable of handling a decent number of concurrent users.**

### Graphical User Interface

![image](https://github.com/orkrahman97/Performance_Testing_JMeter/assets/67518144/b51efeb8-fc11-4b2a-abe4-0a53dffcbd65)

![image](https://github.com/orkrahman97/Performance_Testing_JMeter/assets/67518144/013595a5-2b3b-4399-be27-06471f866668)

![image](https://github.com/orkrahman97/Performance_Testing_JMeter/assets/67518144/6916e3c8-93a6-4c85-bcbd-fddd8fc79993)

![image](https://github.com/orkrahman97/Performance_Testing_JMeter/assets/67518144/59a33dd6-f181-4cd1-9b4e-578bbbfaabe5)

We achieved a 99% accuracy rate by reducing the workload and increasing User 100.  

![image](https://github.com/orkrahman97/Performance_Testing_JMeter/assets/67518144/b53af7e0-09ef-43cc-b81e-f4c9fd5ec3c0)

when we increased the number of users to 150, we encountered a 5% error rate. Therefore, we can consider this value as the ideal one. If we increase the user the accuracy will reduce

![image](https://github.com/orkrahman97/Performance_Testing_JMeter/assets/67518144/26784ee4-7df0-4bd3-bd49-fa6e74a333b4)



## NON-graphical User Interface

![image](https://github.com/orkrahman97/Performance_Testing_JMeter/assets/67518144/4181eece-ed12-4113-997d-2d9c5382b947)

![image](https://github.com/orkrahman97/Performance_Testing_JMeter/assets/67518144/f47ffeaf-de59-43f4-ad8f-517a7720636b)

![image](https://github.com/orkrahman97/Performance_Testing_JMeter/assets/67518144/303f430d-acad-4d77-8fef-3b684991ece9)



# Stress Test
### Test:1 For 100 users and a response assertion of 200, as evidenced by the 5.50% error rate 
![image](https://github.com/orkrahman97/Performance_Testing_JMeter/assets/67518144/e5690f92-5784-43fd-858f-c36e0cde47bc)

 
### **Stress Testing Report**
### **Test-1 (Taking the ideal Response Assertion of 200)**
**Number of Users: 100**
**Response Assertion: 200**
**Test Results:**
**Test: pass**
**Result: 5.50% error rate**
**Analysis: On the homepage of the website, we deal with 100 users and response assertion set to 200, the system performed well, with a 5.50% error rate. This indicates that the system can handle the specified load and meet the performance expectations. The stress test was successful, and the system was found to be working properly under these conditions.**



### Test-02 For 150 users and a response assertion of 200, as evidenced by the 1.00% error rate  **

![image](https://github.com/orkrahman97/Performance_Testing_JMeter/assets/67518144/8e11dbba-8842-47c6-8a25-82165bfbb75f)

### **Stress Testing Report**
### **Test-2 (Taking the ideal Response Assertion of 200)**
**Number of Users: 150**
**Response Assertion: 200**
**Test Results:**
**Test: pass**
**Result: 1% error rate**
**Analysis: On the homepage of the website, we deal with 150 users and response assertion set to 200, the system performed well, with a 1.07% error rate. This indicates that the system can handle the specified load and meet the performance expectations. The stress test was successful, and the system was found to be working properly under these conditions.**



### Test-03 For 200 users and a response assertion of 200, as evidenced by the 7.58% error rate**
 
![image](https://github.com/orkrahman97/Performance_Testing_JMeter/assets/67518144/9ff4292c-2215-423c-bb5a-e2c64e7c5d9d)

 
 
### **Stress Testing Report**
### **Test- 3 (Taking the ideal Response Assertion of 200)**
**Number of Users: 200**
**Response Assertion: 200**
**Test Results:**
**Test: pass**
**Result: 7.58 % error rate**
**Analysis: On the homepage of the website, we deal with 200 users and response assertion set to 200, the system performed well, with a 7.58% error rate. This indicates that the system can handle the specified load and meet the performance expectations. The stress test was successful, and the system was found to be working properly under these conditions.**

### Test-04 For 200 users and a response assertion of 201, as evidenced by the 100% error rate**
![image](https://github.com/orkrahman97/Performance_Testing_JMeter/assets/67518144/a756b4b6-d0bf-432c-846b-af0f9a6358b5)

### **Stress Testing Report**
### **Test-4 (Taking Response Assertion of 201)**
**Scenario: Response Assertion 201**
**Number of Users: 200**
**Response Assertion: 201**
**Test Results:**
**Test: Fail**
**Result: 100% error rate**
**Analysis: In this scenario, we increased the response assertion to 201. Unfortunately, the system experienced a 100% error rate.**
**I observe that a response assertion of 200 users with a maximum of 200 users is the ideal configuration for the Bangla Puzzle website. Beyond this number of users, performance might drop and error rates might increase.**



