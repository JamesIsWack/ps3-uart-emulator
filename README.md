# ps3-uart-emulator
Usermode emulator for the Playstation 3 SYSCON UART
# Syscall info
This project is going to take advantage of the following Hypervisor Syscalls:
  - Syscall 101 [lv1_read_virtual_uart](https://www.psdevwiki.com/ps3/HV_Syscall_Reference#lv1_read_virtual_uart)
  - Syscall 102 [lv1_write_virtual_uart](https://www.psdevwiki.com/ps3/HV_Syscall_Reference#lv1_write_virtual_uart)
  - Syscall 103 [lv1_set_virtual_uart_param](https://www.psdevwiki.com/ps3/HV_Syscall_Reference#lv1_set_virtual_uart_param)
  - Syscall 104 [lv1_get_virtual_uart_param](https://www.psdevwiki.com/ps3/HV_Syscall_Reference#lv1_get_virtual_uart_param)<br>
  
and
  - Syscall 105 [lv1_configure_virtual_uart_irq](https://www.psdevwiki.com/ps3/HV_Syscall_Reference#lv1_configure_virtual_uart_irq)<br>
  
As well as COBRA SYSCALL 8.
