+++
title = "✈️ Airport Network Epidemic Simulation"
date = "2022-12-20"
description = "A Unity-based simulation modeling epidemic spread within an airport network."
[taxonomies]
tags = ["Unity", "CSharp", "Simulation", "3D", "Academic"]
[extra]
cover.image = "images/airport-network-epidemic-cover.gif"
cover.alt = "Airport Network Epidemic Simulation"
category = "Projects"
+++

✨ **Airport Network Epidemic** is a Unity-based simulation modeling how an epidemic spreads through a network of airports. It provides insight into disease propagation and the interconnectedness of global travel hubs.

{% admonition(type="warning", title="Disclaimer") %}
This project is old (2022) and is not an accurate depiction of a real world epidemic.

Although you can try the final version in the latest release, the final project itself was lost. You can only access this old project version on GitHub with other added scripts that were only present in the newer lost project.
{% end %}

💻 **GitHub Repository**

<a href="https://github.com/marcusaasjensen/airport-network-epidemic">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=marcusaasjensen&repo=airport-network-epidemic&theme=github_dark_dimmed" alt="Airport Network Epidemic Repo"/>
</a>

---

## 🎯 Key Features

- 🛫 **3D Airport Network Simulation**: visualize airplanes moving through the airport network.
- 🦠 **Epidemic Spread Modeling**: simulate how infectious diseases propagate over time.
- ⚙️ **Customizable Parameters**: adjust infection rates, cleaning rates, number of airports.
- 📊 **Real-Time Visualization**: watch the dynamic network changes as the epidemic progresses with a legend graph.

---

## ⚙️ Parameters

- 🦠 Chance of Airplane Getting Virus (0 to 1): probability that an airplane becomes contaminated with the virus.

- ∆T Virus Infection Delta T (in days): time before a new airplane contamination occurs at a contaminated airport.

- 🛫 Number of Airports: total number of airports connected as a complete graph in the simulation.

- 🧼 Chance of Cleaning the Virus (0 to 1): effectiveness of cleaning measures at airports.

- 😷 Chance of Cleaning During Lockdown (0 to 1): increased effectiveness of cleaning measures during a lockdown situation.

- ∆T Cleaning Delta T (in days): time before a new cleaning session.

---

## 📽️ Demo

Here is a cliché simulation of an epidemic with 30 connected airports. The virus is extremely contagious everyday and cleaning measures are negligeable during an unknown epidemic. When an airport is in lockdown, cleaning measures are taken seriously.

![Simulation Demo](/images/airport-network-epidemic-demo.gif)

---

## 🛠️ Development

Built with:

- 🎮 **Unity 3D**
- 🧩 **C#** for simulation logic

---

## 🔧 Setup

1. Extract the `airport_network_epidemic.zip` file.  
2. Launch the `Virus_Airport_Network_Simulation.exe` file.  
3. Define the parameters you would like.  
4. Click on the **Start Simulation** button.  
5. Click on airports to toggle their lockdown state.  
6. If the app starts to lag, press **Spacebar** to stop updating the stats graph.  
7. Close the app any time with the close button.

---

## 🙏 Acknowledgments

- Thank you to my professor **Mr. Donati** for assisting the project's evolution.  
- Props to my dear friend [**Marc Pinet**](https://marcpinet.fr) for being part of the student group. He also made an awesome epidemic modeling project using Python which was part of our larger presentation: [epidemic-modeling](https://github.com/marcpinet/epidemic-modeling).
