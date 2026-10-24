---
layout: post
title:  "engineering 1: general"
date:   2000-01-03 00:31:00 +0000
categories: jekyll update
---

* [engineering design process](#engineering-design-process)
* [power & energy technology](#power-technology)
* [transport & aerospace technology](#transport-technology)
* [materials science & construction](#materials-and-construction)
* [smart home & consumer technologies](#technologies-in-the-home)
* [sound, optics & vision systems](#sound-and-vision)
* [communications & network infrastructure](#communications-technology)

## Engineering design process

Engineers follow a different process to the scientific inquiry called the engineers design process. 
1. Define problem
2. Background research
3. Determine design specs and constraints
4. Design statement: Brainstorm ideas, evaluate solutions, chose solution
5. Design and Make Prototype
6. Test and Evaluate prototype 
7. Iterate to find best solution


## Power technology
### Water supply
1. water intake: 
2. coagulation
3. flocculation
4. sedimentation
5. filtration
6. chlorination
7. storage

### Oil refineries
1. crude oil 
2. oil enters column
3. distilation
4. vapour rises
5. tray colllection

### Generators
- AC generators
- DC generators

### Motors
- Electric motors

### Power stations
1. Fuel supply: Coal is crushed and fed into a large furnace to be burned. 
2. Furnace: Water running through tubes in the boiler is heated to an over 500C at very high pressure. Waste gasses pass through an electrostatic precipitator and desulphurisation plant to clean.
3. Turbine: the high pressure steam turns the fan blades of steam turbines with great force and speed. This rotational motion is transmitted to the generator by driveshaft.
4. Generator: generator's rotor spins thousands of times each minute, producing an alternating current (AC), typically with a voltage of 25,000V. 
5. Electricity supply: voltage of electricity is greatly increased by a step-up transformer. This improves efficiency as the electricity is transmitted away via power lines.
6. Cooling tower: steam is cooled in the condenser then sprayed into cooling towers, where most of the water cools and is piped back for re-use. 

<img src="/imgs/science/power_stat.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Electricity supply
1. Power station: a generator located in a power station converts kinetic energy into electrical energy. This produced AC electricity - 25,000V
2. Grid substation: A grid substation uses step up transformer to increase voltage to 400,000V. The higher the voltage the less energy lost as heat from resistance.
3. High voltage pylon lines: steel-reinforced aluminum pylons made with glass/ceramic insulators to stop electricity traveling to the ground.
4. Direct supply to industry: some factories want high voltage!
5. Distribution substation: a step down transformer used to bring voltage down -> industrial and commercial customers.
6. Domestic supply: a network of distribution lines supplies electricity to houses. pole mounted transformers locally bring the voltage down to the home's fusebox.

<img src="/imgs/science/elec_grid.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Nuclear power
1. Uranium fuel rods: Hundreds of metal rods grouped into bundles contain small pellets of uranium fuel. They are lowered into reactor core.
2. Chain reaction: Unstable uranium nuclei break down, releasing heat and emitting neutrons. These collide with further nuclei, creating a chain reaction that provides a huge amounts of energy.
3. Control rods: control rods modify the speed of chain reaction. When lowered in among the fuel rods they absorb the free neutrons to slow down the reaction.
4. Creating steam: heated by the reactor core, the water flows into a heat exchanger, giving up its energy to a second closed system of piping that carries cold water. The cold water is turned into hot steam, under high pressure.
5. Turning the turbine: housed in a turbine hall, the turbine's fan blades are turned by the high-pressure steam from the heat exchanger. 
6. Power supply: the electricity generator is driven by the turbine's drive shaft. A transformer increases the voltage so it can be carried away.

<img src="/imgs/science/nuclear.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Wind power
1. Turbine blades: mounted on a freely turning axis, the propeller like blades catches the air and spin round. As they move they turn a central drive shaft. The angle or pitch of turbine blades can eb altered to adjust their speed. 
2. Gearbox: converts low speed rotation into high speed rotation to turn generator.
3. Generator: takes mechanical energy from driveshaft and turns into electrical energy.
4. Electric current: produced by generator taken by a cable
5. Increasing voltage: step up transformer used to get high voltage to be passed to the power grid.

Micro-generation
small scale renewable energy systems use free standing or roof mounted roof wind turbines.

### Water and geothermal power
1. Cold water pumped
2. Hot water returns
3. Heat exchanger
4. Power generation

### Solar energy and bio-energy
1. Solar energy: sunlight comprises tiny energy packets called photons. When photons hit a solar panel, made of dozens of PV cells, they transfer energy to electrons that then flow via conductors through an external circuit as an electrical current.
2. Converting current (DC->DC): An inverter converts electricity from the panel DC into AC, which is then usable by the home.
3. Distributing power: the electricity is sent from the main panel around the home. The panel can accept electricity from the local grid when the solar panels do not meet demand.
4. Measuring power: a smart meter keeps track of energy generation and electricity use in both directions.
5. Connecting to the grid: Any excess electricity produced by the solar panels is sent to the power grid and credited to householder.

<img src="/imgs/science/pv.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Batteries
batteries are a portable store of chemical energy that can converted into electrical energy. Primary (single use) and secondary(rechargeable). 

1. chemical reactions: when a battery is connected to an electric circuit, a chemical reaction makes the metal atoms lose electrons. These are attracted to and gained by a chemical paste called electrolyte.
2. electrons gather: free electrons are drawn towards an anode, creating an imbalance with a deficit of electrons at the anode and an excess at the anode. The electrons freed by the chemical reaction move towards the anode inside the battery but cannot get any further until an eternal circuit is connected.
3. migrating electrons: the external circuit connecting the anode and cathode provide a path along which the electrons can flow, producing an electric current. Along the way, this current can be used to power an electrical device.
4. incoming electrons: the electrons re-enter the battery via the cathode. The flow continues until the store of chemicals is exhausted.

Recharging:
when a battery is plugged into a charger, a current is passed through in the opposite direction that was discharging. This moves electrons back to where they started, recharging the battery.

Lithium ion batteries
- large number of electrons in reactive metal lithium
- lithium has a low weight but high energy density -> good power to weight ratio for batteries  that can withstand hundreds of discharge and recharge cycles. 

<img src="/imgs/science/batt.png" alt="Universe" style="width: 100%; height: auto; display: block">

## Transport technology

### How a car works
A car is a collection of systems that generates power in and engine and transmit it to the wheels. Other systems allow the driver to control the car by turning the wheels to change direction and by applying brake force to either slow down or stop.

1. engine: internal combustion engine - starting the engine ignites the fuel and releases energy. This moves pistons, which turns the engine's crankshaft. A flywheel attached to the crankshaft smooths out the power provided by the pistons
2. clutch: The driver must disconnect the clutch then releases clutch, allowing the engine to turn the wheel.
3. gearbox: piston engines work most efficiently at relatively high speeds, so gears are necessary to reduce this to a slower rotational speed needed for car's wheels. Each gear gives a different range of speeds. First gear is normally selected to get car moving.
4. driveshaft: a long driveshaft connects gearbox to rear wheels. In front wheel car, engine sits on top of the front wheels and turns them via short driveshaft, differential and half shafts.
5. steering: rack and pinion - turning car's steering wheel rotates a pinion - small round gear. it's teeth engage the teeth on a flat bar called a rack. 
5. braking: disc brakes - a disc is fixed to each wheel, when the wheel spins, so does the disc. When braking applied, hydraulic fluid forces brake pads, mounted on calipers to push against the disc to slow wheel down.

<img src="/imgs/science/car.png" alt="Universe" style="width: 100%; height: auto; display: block">

#### Internal combustion engines
a heated fuel-air mixture (petrol and air). 
1. intake
2. compression
3. power - spark plug
4. exhaust

### Electric and hybrid cars
electric motors connected to a rechargeable battery.
<img src="/imgs/science/electric_car.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Radar
high frequency radio waves are sent out then reflected back.
<img src="/imgs/science/radar.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Speed cameras
high frequency radio waves are sent out then reflected back.

### Trains
- electric trains, use overhead cables or third rail
<img src="/imgs/science/train.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Sailboats
<img src="/imgs/science/sailboats.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Submarines
<img src="/imgs/science/submarines.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Jet engines and rockets
<img src="/imgs/science/jet_engine.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Aeroplanes
<img src="/imgs/science/air_plane.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Helicopters
<img src="/imgs/science/helicopter.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Drones
<img src="/imgs/science/drones.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Space probes
<img src="/imgs/science/space_probes.png" alt="Universe" style="width: 100%; height: auto; display: block">

## Materials and construction

### Plastics
<img src="/imgs/science/plastic.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Composites
<img src="/imgs/science/composites.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Bridges
<img src="/imgs/science/bridges.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Tunnels
<img src="/imgs/science/tunnels.png" alt="Universe" style="width: 100%; height: auto; display: block">


## Technologies in the home
### Utilities in the home
Utilities include power, heating, water and communications services supplied to homes. They are usually provided by external companies, although some properties may have an independent water supply or heating source.

**Central heating**
water is heated often using an oil or gas fired boiler, and then circulated in a closed system of pipes and radiators to warm rooms. Thermostats monitor temperature to ensure the desired heat level is maintained.

**Electricity supply**
Electricity is metered and distributed around a home by a consumer unit.
<img src="/imgs/science/home_util.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Heating

1. Gas and air: Air is drawn in by the fan as gas is supplied from the gas pipe to the burner. A pilot light burns, ready 

<img src="/imgs/science/home_boil.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Microwave ovens
<img src="/imgs/science/home_micro.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Refrigeration 
<img src="/imgs/science/home_refridge.png" alt="Universe" style="width: 100%; height: auto; display: block">


### Washing machine
<img src="/imgs/science/home_wash.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Digital home
<img src="/imgs/science/home_digi.png" alt="Universe" style="width: 100%; height: auto; display: block">


## Sound and vision

### Waves
<img src="/imgs/science/sound_waves.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Microphones and loudspeakers
<img src="/imgs/science/sound_speak.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Digital sound


### Digital cameras
<img src="/imgs/science/sound_camera.png" alt="Universe" style="width: 100%; height: auto; display: block">

## Communications technology
### radio signals
<img src="/imgs/science/comm_radio.png" alt="Universe" style="width: 100%; height: auto; display: block">


### radios
<img src="/imgs/science/comm_radio2.png" alt="Universe" style="width: 100%; height: auto; display: block">

### telephones
<img src="/imgs/science/comms_tele.png" alt="Universe" style="width: 100%; height: auto; display: block">


### television broadcasting 
<img src="/imgs/science/comms_tele3.png" alt="Universe" style="width: 100%; height: auto; display: block">

### televisions

### satellites
### satellite navigation
<img src="/imgs/science/comms_tele4.png" alt="Universe" style="width: 100%; height: auto; display: block">

### internet
<img src="/imgs/science/comms_internet.png" alt="Universe" style="width: 100%; height: auto; display: block">

### world wide web
<img src="/imgs/science/comms_www.png" alt="Universe" style="width: 100%; height: auto; display: block">

### email
<img src="/imgs/science/comms_email.png" alt="Universe" style="width: 100%; height: auto; display: block">

### Wifi
<img src="/imgs/science/comms_wifi.png" alt="Universe" style="width: 100%; height: auto; display: block">

### mobile devices
<img src="/imgs/science/comms_phone.png" alt="Universe" style="width: 100%; height: auto; display: block">

### smart phones
<img src="/imgs/science/comms_phone2.png" alt="Universe" style="width: 100%; height: auto; display: block">


