# F.L.O.O.R

**FICSIT Logistics & Optimal Organizational Router**

F.L.O.O.R is a modern browser based 2D factory layout planner for Satisfactory. It provides a top down grid where you can place buildings, organise factory floors, connect machinery with conveyors and pipelines, calculate construction costs, and save complete factory plans.

<img width="1856" height="925" alt="image" src="https://github.com/user-attachments/assets/4c8cf1d0-753e-477c-bb95-52617a5aafcb" />

Open the planner here: https://mrmysteryv.github.io/F.L.O.O.R/

## Features

### Factory layout planning

* Place Satisfactory buildings on a metre based grid
* Move, rotate, copy, paste, and delete buildings
* Select individual buildings or multiple buildings
* Add buildings to the current selection with `Ctrl + Left Click`
* Box-select buildings with `Shift + Drag`
* Move multiple selected buildings together
* Add custom text labels to the layout

### Conveyors and pipelines

* Draw conveyor belts between building ports
* Draw pipelines between compatible fluid ports
* Snap connectors to building inputs and outputs
* Select conveyor and pipeline tiers
* Edit connector endpoints
* Add conveyor lifts and vertical pipelines between floors
* Choose whether lifts travel upwards or downwards

### Multi-floor factories

* Create floors above or below the reference floor
* Switch between floors using the floor selector
* Place buildings and connectors independently on each floor
* Connect floors using conveyor lifts and vertical pipelines
* Track floor height in metres

### Building cost calculator

* Calculates the materials required for the current plan
* Includes building construction costs
* Includes foundation costs
* Includes conveyor and pipeline costs by tier
* Displays item quantities in a checklist
* Provides per building and per floor breakdowns

### Saving and loading

* Export complete layouts as `.sfactory` files
* Import previously saved factory plans
* Automatically save the current layout in browser local storage
* Restore the layout after refreshing or reopening the page
* Clear the entire grid from the settings menu

### Batch placement

* Choose multiple building types and quantities
* Start a guided batch-placement session
* Place repeated machines without reselecting each building from the menu

## Controls

| Control              | Action                                              |
| -------------------- | --------------------------------------------------- |
| `Left Click`         | Select or place                                     |
| `Ctrl + Left Click`  | Add or remove a building from the current selection |
| `Shift + Drag`       | Box-select buildings                                |
| `Right Mouse + Drag` | Pan the camera                                      |
| `Mouse Wheel`        | Zoom in or out                                      |
| `R`                  | Rotate the current building or selection            |
| `L`                  | Activate the label tool                             |
| `Ctrl + C`           | Copy selected buildings                             |
| `Ctrl + V`           | Begin placing the copied group                      |
| `Delete`             | Delete the selected object or objects               |
| `Escape`             | Cancel the current action                           |

Input and output pills are temporarily disabled while `Ctrl` is held or while multiple buildings are selected. This prevents connector interactions from interfering with multi selection.

## Running the planner

### Option 1: 
Open the webpage directly at https://mrmysteryv.github.io/F.L.O.O.R/

### Option 2 (no wifi needed): 
Clone the repository and open index.html

## Local autosave

The current plan is stored in browser localStorage. The saved data includes everything.
The exported `.sfactory` file should be used if transferring between browsers/devices and is more reliable for saving very large factories.

## Disclaimer

F.L.O.O.R is a fan made planning tool and is not affiliated with or endorsed by Coffee Stain Studios.

Satisfactory and its related names, images, and assets are the property of their respective owners.
