# GL-C-006P_mini_fix
GL-C-006P (mini) bricked after OTA update fix

1. extract content of GL-C-006P_mini_fix.7z into zigbee2mqtt root folder where configuration.yaml is placed
2. rename my_index.json_to002 to my_index.json
3. set zigbee2mqtt->settings->OTA updates->OTA index override file name to my_index.json, submit and apply
4. restart z2m
5. OTA->Check for new updates and run update, this will update FW to patched GL-C-002P version
6. rename my_index.json_to006_mini to my_index.json
7. OTA->Check for new updates and run update, this will update FW to GL-C-006P mini version
   
