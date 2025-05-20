# vworldrevgeocd
# This file contains metadata for your plugin.

# This file should be included when you package your plugin.# Mandatory items:

[general]
name=VWorld_Reverse_Geocoding
qgisMinimumVersion=3.0
description=Obtaining address information using the VWorld reverse geocoding API based on the coordinates (longitude, latitude) of a point feature class.
version=0.1
author=KIM SUNGHYUN/Geogreen21 Co.
email=shk7773@naver.com

about=A custom plugin that uses the coordinates of point features to automatically populate address information. Utilizing the VWorld API provided by the Ministry of Land, Infrastructure, and Transport, you can perform reverse geocoding directly on the map without having to work outside of your GIS software. \n ================================================= \n포인트 피쳐클래스의 좌표계를 사용하여, 주소 정보를 자동으로 채우는 플러그인입니다. 국토교통부에서 제공하는 VWorld API를 활용하여, GIS 소프트웨어 외부에서 작업할 필요 없이 지도에서 바로 리버스 지오코딩을 수행할 수 있습니다.

tracker=http://bugs
repository=http://repo
# End of mandatory metadata

# Recommended items: VWordl API Key

hasProcessingProvider=no
# Uncomment the following line and add your changelog:
# changelog=

# Tags are comma separated with spaces allowed
tags=geocoding, field, point, project, adress, API, VWorld

homepage=https://www.geogreen21.com/
category=Plugins
icon=icon.png
# experimental flag
experimental=False

# deprecated flag (applies to the whole plugin, not just a single version)
deprecated=False

# Since QGIS 3.8, a comma separated list of plugins to be installed
# (or upgraded) can be specified.
# Check the documentation for more information.
# plugin_dependencies=

Category of the plugin: Raster, Vector, Database or Web
# category=

# If the plugin can run on QGIS Server.
server=False

