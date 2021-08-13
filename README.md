# Help-Menu-FOR-python-Embed-

import discord
from discord import colour
from discord import embeds
from discord import client
from discord.ext import commands
from discord.ext import tasks
from asyncio import *
import randomimport os
from discord.ext.commands.errors import DisabledCommand
client = commands.Bot(command_prefix = "!")
client.remove_command("help")
#----------Code-----------#
 @client.command() async def help(ctx):     help = discord.Embed(title = "Help Menu" , description = "HELP " , colour =0xED102B)    
 await ctx.send(embed=help)
