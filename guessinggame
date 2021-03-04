#!/usr/bin/env bash

echo "[Welcome to GUESSING-GAME v1.0]"

function ask {
	echo "Please enter the number of files in the curr directory:"
	read guess
    files=$(ls -1 | wc -l)
}

ask

while [[ $guess -ne $files ]]
do
	if [[ $guess -lt $files ]] 
	then
		echo "Too low."
	else
		echo "Too high."
	fi
	ask
done

echo "Well done! Correct answer! Here is the list of files:"
echo "---------" && ls -1
