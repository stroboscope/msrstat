# msrstat

Experimental tool to dynamially observe per-cpu *performance counters*
statistics. It reads counters via MSR. Run `msrstat -h` for help.

### Requirements
*ruby* 1.8 or higher. Kernel compiled with CONFIG_X86_MSR. Root permissions to
access /dev/cpu/x/msr.

### License
GPL

(c) 2014, abc @ telekom.ru.

