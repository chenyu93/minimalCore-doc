# API Reference

### npc_move_to_async
Query the activate trigger boxes of given npc

 -  Input
    -  name[`string`]: unique id for npc 
    -  location[`Tuple<float, float, float>`]: world position
    -  speed[`float`]: move maxinum speed, e.g., 100(walk), 300(run)
 - Output 
    - `None`

### get_npc_pos_vel
Query the location of the NPC and the instant velocity.

 -  Input
    -  name[`string`]: unique id for npc 
 - Output 
    -  `Tuple<float, float, float, float, float, float>`: Location.X Location.Y Location.Z Velocity.X Velocity.Y Velocity.Z (world coordinates)

### get_npc_active_triggers
Query the activate trigger boxes of given npc

 -  Input
    -  name[`string`]: unique id for npc 
 - Output 
    -  `vector<string>`: return currenly activated trigger