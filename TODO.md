- look at using IPMininet instead of base mininet?
- create separate DebugMixin class that adds debug tags to BaseModbusDevice
- have RemoteDevice classes that make modbus request whenever their getattr() is called
   - and send requests whenever their setattr() is called