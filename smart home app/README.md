# README: Smart Home Management Design

## Research: Trends and User Challenges in Smart Home Management

### Current Trends
- **Voice-Controlled Interfaces:** Users are increasingly relying on voice assistants for hands-free operation of their smart home devices.
- **Unified Platforms:** A trend is emerging towards centralized systems that manage all smart devices through a single interface.
- **Energy Efficiency Focus:** There is a heightened emphasis on monitoring and reducing energy consumption.
- **Security and Privacy:** Concerns about data security and user privacy are becoming more prominent.
- **Device Fragmentation:** Managing a wide variety of devices and applications remains complicated.
- **Customization Limits:** Existing customization options often do not fully meet user needs.
- **Routine Automation:** Users are looking for applications that can automate daily tasks and streamline routine management.
- **Advanced Features for Experienced Users:** IoT users seek more intuitive interfaces and advanced functionalities.

### Pain Points
- **User-Friendly UI:** There is a strong need for an intuitive interface that makes navigation and control seamless for users.
- **Energy Management:** Current tools for tracking and managing energy consumption are insufficient.
- **Real-Time Cost Tracking:** Users desire real-time comparisons between estimated and actual energy costs.
- **Routine Configuration:** There is a need for better tools to schedule and automate device routines.

## Design Explanation

### Home Screen Overview
1. **Top Sections: Usage Tracking**
   - **Top-Right Section:** Displays today's electricity usage, allowing users to monitor daily consumption.
   - **Top-Left Section:** Shows the entire month's electricity usage, helping users track their overall consumption trends.
   - **Purpose:** These sections, combined with analytical charts, encourage users to be mindful of their energy consumption and make improvements.

2. **Quick Access Section**
   - **Frequent Devices:** Displays the 4 most frequently used devices for easy access.
   - **All Devices:** Clicking the "All Devices" CTA reveals a full list of 10-16 devices.
   - **Benefit:** This reduces screen-switching, allowing users to find and control their devices more quickly and efficiently.

3. **Favorite Scenes**
   - **Custom Scenes:** Displays user-created scenes in a scrollable section for easy access to preferred settings.
   - **Empty State:** If no scenes are created, or if the user does not wish to use this feature, a placeholder rectangle with the text "Make your first scene" and a "+" CTA is shown to encourage scene creation.

### Device Screen Overview
1. **Add New Device**
   - **CTA at the Top:** The screen features an "Add a New Device" CTA at the top.
   - **Navigation:** Clicking this CTA takes the user to a new screen for adding devices.

2. **Connected Devices by Room**
   - **Scroll Format:** All connected devices are displayed in a scrollable format, organized by room.
   - **Benefit:** This layout makes it easier for users to find and manage devices based on their room location.

### AC Screen Overview
1. **Access Points**
   - **From Device Screen:** The AC screen can be accessed by clicking on the AC icon in the device screen.
   - **From Quick Access:** Alternatively, it can be accessed from the quick access section on the home screen.

2. **Comprehensive Remote Features**
   - **User-Friendly Layout:** All remote control features for the AC are presented in an easy-to-understand format, ensuring smooth user interaction.

### Security Feature Overview
1. **Door Connection**
   - The security feature allows the user to connect all the doors in their home to the system.

2. **Alarm Activation**
   - When the user activates the alarm feature (e.g., during a family trip or when no one is at home), any door that opens will trigger an alert.

3. **Phone Alerts**
   - **Vibration Alert:** If a door is opened, the phone will vibrate for 10 seconds.
   - **Ringtone Alert:** If the phone is not in vibrate mode, it will play a ringtone to notify the user.

4. **Missed Alerts**
   - If the user misses the alert, a notification will appear in the notification panel for later reference.

5. **Feature Access**
   - This security feature can be accessed from the device screen for easy management.

6. **Auto-Lock Functionality**
   - If a door remains open for more than 15 seconds and no family member is nearby, the door will automatically lock (if equipped with an auto-lock feature).
