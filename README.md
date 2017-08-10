# Stylometry

This repository contains issues for the different stages in the Nederlab Stylometry project.
The project consists of the following stages:

1. StyloFreqs (data) - Figure out which frequency tables are needed for the following stages
1. StyloCaller ("R") - Make "R" function to call selected Stylo parts using the tables from step 1
1. StyloBroker (broker) - Find out which broker queries need be used to arrive at the frequency tables in step 1
1. StyloUI (JavaScript) - User interface that allows the Nederlab onderzoeksportaal user to indicate which frequency tables need to be made. The interface should also contain an export function.
1. StyloService (Java, R) - Web service that receives a frequency table from the StyloUI, uses Stylo in "R", and returns data in the right format
1. StyloPortaal (...) - Integrate all Nederlab components for the onderzoeksportaal
