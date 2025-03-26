<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Future Flight: Building an Affordable Drone</title>
</head>
<body>

<h1 align="center">🚁 Future Flight: Building an Affordable Drone</h1>
<h2 align="center">🌍 Making Drone Technology Accessible for Everyone</h2>

<hr>

<h2>🔍 The Problem</h2>

<p>Drones have transformed industries, from aerial surveillance to precision agriculture. However, high costs and complex designs make them <b>inaccessible to hobbyists, students, and innovators</b>.</p>

<p>There is a need for an <b>affordable, open-source, and easy-to-build</b> drone that bridges the gap between learning and real-world applications.</p>

<hr>

<h2>💡 The Smart Solution</h2>

<p><b>Future Flight</b> is a low-cost, customizable drone powered by the <b>KK2.1.5 flight controller</b>, designed for smooth and stable flight.</p>

<p>With features like <b>precision control, modular design, and wireless operation</b>, it serves as an educational tool and a foundation for advanced drone applications.</p>

<hr>

<h2>🚀 Features</h2>

<ul>
    <li>✅ <b>Stable Flight Control</b> – KK2.1.5 ensures smooth and responsive maneuvers.</li>
    <li>✅ <b>Wireless Operation</b> – FlySky FS-i6 transmitter provides precise control.</li>
    <li>✅ <b>Efficient Power</b> – 2200mAh LiPo battery optimizes flight time.</li>
    <li>✅ <b>Expandable Design</b> – Easily integrate additional sensors or modules.</li>
    <li>✅ <b>DIY-Friendly</b> – Designed for beginners and experts alike.</li>
</ul>

<hr>

<h2>🛠️ How It Works</h2>

<ul>
    <li>🔹 Assemble the frame and install the <b>KK2.1.5 flight controller</b>.</li>
    <li>🔹 Connect and calibrate the <b>Emax motors</b>, ESCs, and FlySky FS-i6 transmitter.</li>
    <li>🔹 Configure flight parameters and conduct <b>test flights</b> for optimization.</li>
    <li>🔹 Modify and expand the drone for <b>custom applications</b>.</li>
</ul>

<hr>

<h2>📜 Project Components</h2>

<ul>
    <li><b>KK2.1.5 Flight Controller</b></li>
    <li><b>Emax Brushless Motors</b></li>
    <li><b>30A ESC (Electronic Speed Controllers)</b></li>
    <li><b>2200mAh 11.1V LiPo Battery</b></li>
    <li><b>FlySky FS-i6 Transmitter & Receiver</b></li>
    <li><b>Drone Frame & Propellers</b></li>
</ul>

<hr>

<h2>🖥️ Arduino Code</h2>

<pre>
#include &lt;Servo.h&gt;

Servo esc1, esc2, esc3, esc4;

void setup() {
    esc1.attach(9);
    esc2.attach(10);
    esc3.attach(11);
    esc4.attach(12);
    
    esc1.writeMicroseconds(1000);
    esc2.writeMicroseconds(1000);
    esc3.writeMicroseconds(1000);
    esc4.writeMicroseconds(1000);
    delay(5000); 
}

void loop() {
    esc1.writeMicroseconds(1500);
    esc2.writeMicroseconds(1500);
    esc3.writeMicroseconds(1500);
    esc4.writeMicroseconds(1500);
}
</pre>

<hr>

<h2>🏆 Project Outcomes</h2>

<ul>
    <li>🚁 Successfully built a <b>cost-effective, functional drone</b> with stable flight.</li>
    <li>🎓 Provides an <b>educational platform</b> for learning drone technology.</li>
    <li>🔧 Open-source design enables <b>customization and future enhancements</b>.</li>
</ul>

<h2>🧩 Project Components</h2>

<p>Below is a list of the key components used in building the Future Flight drone:</p>

<ul>
    <li>🔋 <b>LiPo Battery (2200mAh, 11.1V, 3S)</b> – Ensures reliable and long-lasting power for flight operations.</li>
    <li>🛠️ <b>EMAX Motors</b> – High-performance motors designed for stable and efficient propulsion.</li>
    <li>⚙️ <b>30A ESCs</b> – Precision electronic speed controllers for optimal motor control.</li>
    <li>📡 <b>FLYSKY FS-i6 Transmitter & Receiver</b> – Enables seamless wireless communication for flight control.</li>
    <li>📦 <b>KK2.1.5 Flight Controller</b> – The core of the drone’s navigation and stability management.</li>
    <li>📊 <b>GPS Module</b> (optional) – For enhanced autonomous navigation and position hold.</li>
    <li>🖥️ <b>Onboard Sensors</b> – Includes accelerometers, gyroscopes, and barometers for real-time flight adjustments.</li>
</ul>

<p>Here’s a visual breakdown of the components:</p>

<hr>

<h2>🧩 Component List</h2>

<p>Below is a list of the key components used in the Future Flight drone project:</p>

<table align="center" border="0" cellpadding="10">
    <tr>
        <td align="center">
            <a href="https://raw.githubusercontent.com/Rakibul10x/Future-Flight-Building-an-Affordable-Drone/main/component_list.jpg" target="_blank">
                <img src="https://raw.githubusercontent.com/Rakibul10x/Future-Flight-Building-an-Affordable-Drone/main/component_list.jpg" alt="Component List" width="300">
            </a>
            <p>📸 Component List – All the major components used in the drone.</p>
        </td>
    </tr>
</table>

<hr>

<h2>🔌 Schematic Diagram</h2>

<p>Below is the schematic diagram outlining the wiring and connections of the drone's components:</p>

<a href="https://raw.githubusercontent.com/Rakibul10x/Future-Flight-Building-an-Affordable-Drone/main/Schematic%20Diagram.png" target="_blank">
    <img src="https://raw.githubusercontent.com/Rakibul10x/Future-Flight-Building-an-Affordable-Drone/main/Schematic%20Diagram.png" alt="Circuit Schematic" width="80%" style="display:block; margin:auto;">
</a>

<p>This diagram provides a clear understanding of the electrical system's integration, ensuring smooth operation of the drone.</p>

<hr>

<h2>✈️ Flight Test and Performance Analysis</h2>

<p>Watch the performance test of the Future Flight drone. The flight test includes key aspects such as stability, range, and battery life:</p>

<table align="center" border="0" cellpadding="10">
    <tr>
        <td align="center">
            <a href="https://raw.githubusercontent.com/Rakibul10x/Future-Flight-Building-an-Affordable-Drone/main/Flight%20Test%20and%20Performance%20Analysis-1.png" target="_blank">
                <img src="https://raw.githubusercontent.com/Rakibul10x/Future-Flight-Building-an-Affordable-Drone/main/Flight%20Test%20and%20Performance%20Analysis-1.png" alt="Flight Test" width="300">
            </a>
            <p>📸 Flight Test – The drone in action during its first flight.</p>
        </td>
        <td align="center">
            <a href="https://raw.githubusercontent.com/Rakibul10x/Future-Flight-Building-an-Affordable-Drone/main/performance_analysis.jpg" target="_blank">
                <img src="https://github.com/Rakibul10x/Future-Flight-Building-an-Affordable-Drone/blob/main/Flight%20Test%20and%20Performance%20Analysis-2.png" alt="Performance Analysis" width="300">
            </a>
            <p>📸 Performance Analysis – Measuring the drone's flight stability, speed, and efficiency.</p>
        </td>
    </tr>
</table>

<hr>



<h2>🔗 Get Involved & Build Your Own Future Flight Drone!</h2>

<p>🚀 <b>Clone the Repository & Start Building:</b></p>

<pre>
git clone https://github.com/YourUsername/Future-Flight-Drone.git
</pre>

</body>
</html>
