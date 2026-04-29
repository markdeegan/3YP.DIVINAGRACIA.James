# 3YP.DIVINAGRACIA.James

James DIVINAGRACIA 3YP



\### Main program sequence



Wake from Deep Sleep
  v
Read RFID

&#x20; v

Write CSV immediately

&#x20; v

Update LCD

&#x20; v

Try MQTT Upload

&#x20; v
Mark Upload Success
  v

Return to Deep Sleep





\### System fail scenarios that require a device reboot (setting esp32-s3 reset pin high)

* Wi-Fi lost
* ThingsBoard offline
* MQTT timeout
* Power interruption

