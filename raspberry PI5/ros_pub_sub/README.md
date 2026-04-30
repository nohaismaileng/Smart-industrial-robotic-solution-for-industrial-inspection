# ROS Publisher & Subscriber (Python)

This project demonstrates a simple ROS (Robot Operating System) publisher and subscriber using Python.

## 📦 Requirements

* ROS (Noetic recommended)
* Python 3
* rospy
* std_msgs

## 🚀 How to Run

### 1. Start ROS Master

```bash
roscore
```

### 2. Run Talker (Publisher)

```bash
rosrun ros_pub_sub talker.py
```

### 3. Run Listener (Subscriber)

```bash
rosrun ros_pub_sub listener.py
```

## 🧠 What it does

* `talker.py` publishes messages to the topic `/chatter`
* `listener.py` subscribes to `/chatter` and prints received messages

## 📌 Example Output

```
I heard: Hello ROS! Time: 123456.789
```

## 🏗️ Author

Eng Noha
