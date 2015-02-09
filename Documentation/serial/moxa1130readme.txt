This is the Copyright of the original Kernel (it's GPL):

 * MOXA UPort 1130 USB to Serial Hub Driver
 *
 * Copyright (C) 2007 MOXA Technologies Co., Ltd.
 *
 * This driver is based on the Linux io_ti driver, which is
 *   Copyright (C) 2000-2002 Inside Out Networks
 *   Copyright (C) 2001-2002 Greg Kroah-Hartman
 *   Copyright (C) 2004-2006 Al Borchers
 *   Copyright (C) 2014-2015 Vincenzo Di Massa <hawk.it@tiscali.it>
 *   Copyright (C) 2014-2015 Francesco Lorenzini <francescolorenzini1992@gmail.com>
 *   Copyright (C) 2014-2015 Francesco Gabbrielli <francegabb@gmail.com>
 *
 * This program is free software; you can redistribute it and/or modify
 * it under the terms of the GNU General Public License as published by
 * the Free Software Foundation; either version 2 of the License, or
 * (at your option) any later version.


This driver supports the MOXA 1130 converter 
USB/Serial-RS485 on the Linux Kernel.

This code originates from a Moxa release (from the 2.6 era).
The changes from the Moxa version comprise:
- porting to the new kernel driver APIs (usb-serial and termios);
- splitted the firmware in a separate binary file (moxa-1130.fw)
  loaded at device's initialization;
- some aesthetic changes;
- remove all the code not related to MOXA 1130.


