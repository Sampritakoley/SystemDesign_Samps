# SystemDesign_Samps

📬 System Design Concepts: The Mail Distribution Center Analogy
### 1. Scaling the Core Resource (Vertical Scaling)
**<img src="https://github.com/Sampritakoley/SystemDesign_Samps/blob/e5efb5fc4eac143c85bc18b86732dbf0f33d0d8b/image1.png" alt="Image illustrating an upgraded sorting machine" width="300px" height="300px">**
 >Here, the old sorting machine has been significantly upgraded with modern tech, lights, and screens, symbolizing the investment in optimizing a single resource to handle more mail—Vertical Scaling. The same single mailman is operating it, but more efficiently.
### 2. Ensuring Resilience and Redundancy (Single Point of Failure / Master-Slave)
**<img src="https://github.com/Sampritakoley/SystemDesign_Samps/blob/e5efb5fc4eac143c85bc18b86732dbf0f33d0d8b/image2.png" alt="Image illustrating an upgraded sorting machine" width="300px" height="300px">**
  > This image shows one sorting machine sparking and failing, while an identical, active backup machine stands ready, being monitored by another employee. This illustrates the importance of Redundancy to avoid a Single Point of Failure.
### 3. Scaling Out for Capacity (Horizontal Scaling)
**<img src="https://github.com/Sampritakoley/SystemDesign_Samps/blob/e5efb5fc4eac143c85bc18b86732dbf0f33d0d8b/image3.png" alt="Image illustrating an upgraded sorting machine" width="300px" height="300px">**
  > Here we see a vast hall filled with many similar, smaller sorting machines, all working in parallel, with an overhead display showing "HORIZONTAL SCALING IN EFFECT" and high daily volumes. This represents the concept of Horizontal Scaling by adding more resources.
### 4. Specialization (Microservices)
**<img src="https://github.com/Sampritakoley/SystemDesign_Samps/blob/e5efb5fc4eac143c85bc18b86732dbf0f33d0d8b/image4.png" alt="Image illustrating an upgraded sorting machine" width="300px" height="300px">**
  > This overhead view shows different sections of the mail center, each highlighted with a distinct color and labeled for specialized tasks (e.g., "Local Letters," "International Parcels," "Fragile Items"). This clearly illustrates a Microservice Architecture where different teams/machines handle specific mail types, reflecting separation of concerns.
### 5. Distribution and Fault Tolerance (Distributed System)
**<img src="https://github.com/Sampritakoley/SystemDesign_Samps/blob/e5efb5fc4eac143c85bc18b86732dbf0f33d0d8b/image5.png" alt="Image illustrating an upgraded sorting machine" width="300px" height="300px">**
  > This conceptual image shows three distinct mail processing centers in different geographic locations (city, desert, mountains). One in the desert is experiencing a "SYSTEM FAILURE" (symbolized by sparks and a broken connection), but the other two remain operational, illustrating the resilience of a Distributed System and its Fault Tolerance.
### 6. Intelligent Routing (Load Balancing)
**<img src="https://github.com/Sampritakoley/SystemDesign_Samps/blob/e5efb5fc4eac143c85bc18b86732dbf0f33d0d8b/image6.png" alt="Image illustrating an upgraded sorting machine" width="300px" height="300px">**
  > This infographic shows incoming mail trucks being directed by a central "LOAD BALANCER" to different processing centers. One center is highlighted as busy with high latency (red), while another with low latency is chosen (green arrow) for the fastest delivery. This visualizes how a Load Balancer performs Intelligent Routing based on real-time metrics.
### 7. Decoupling and Extensibility
**<img src="https://github.com/Sampritakoley/SystemDesign_Samps/blob/e5efb5fc4eac143c85bc18b86732dbf0f33d0d8b/image7.png" alt="Image illustrating an upgraded sorting machine" width="300px" height="300px">**
  > This final image is a conceptual diagram showing two distinct, complex modules: "Mail Processing & Logistics" and "Customer Tracking & New Services," connected only by a "DECOUPLED INTERFACE." It highlights how new services like "Package Returns" or "Advanced Tracking" can be added to the customer side without impacting the core mail processing, demonstrating Decoupling and Extensibility.
