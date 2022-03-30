.. _ug_build_system_eda_tools:

Interfacing EDA tools
=====================

FuseSoC's main responsibility is to collect and prepare cores for being used with and EDA tool or a series of EDA tools. To accomplish this, FuseSoC hands over an EDAM structure to Edalize and tells Edalize to run the EDA tools. FuseSoC users still need to inform Edalize what tools to run and any particular settings that should be applied when running those tools. There are two API for doing this. The traditional tool-centric API has been available since the launch of Edalize and is documented in :ref:`ug_build_system_tool_options`. The new flow API, which will eventually supersede the old API is documented in the :ref:`ug_build_system_flows` section.
