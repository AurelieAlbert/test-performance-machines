# test-performance-machines

In this repo a collection of notebooks that have been run on various machine : local machine, cluster cal1, pangeo cloud, hal cines HPC and occigen cines HPC.

The results are :

| Operation | Machine | Ressources | Timing |
|-----------|---------|------------|---------|
| Opening of netcdf -  10Tb | Personnal Computer | 8 cores - 34Gb | 9.53s |
| Opening of netcdf -  10Tb | Cluster cal1 | 8 cores - 34Gb | 9.53s |
| Opening of netcdf -  10Tb | HPC hal CNES | 8 cores - 34Gb | 9.53s |
| Opening of netcdf -  10Tb | HPC occigen CINES | 8 cores - 34Gb | 9.53s |
|-----------|---------|-----------|--------------|
| Opening of netcdf -  10Tb | Personnal Computer | 8 cores - 34Gb | 9.53s |
| Opening of netcdf -  10Tb | Cluster cal1 | 8 cores - 34Gb | 9.53s |
| Opening of netcdf -  10Tb | HPC hal CNES | 8 cores - 34Gb | 9.53s |
| Opening of netcdf -  10Tb | HPC occigen CINES | 8 cores - 34Gb | 9.53s |
|-----------|---------|-----------|--------------|


<table>
    <thead>
        <tr>
            <th>Layer 1</th>
            <th>Layer 2</th>
            <th>Layer 3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=4>L1 Name</td>
            <td rowspan=2>L2 Name A</td>
            <td>L3 Name A</td>
        </tr>
        <tr>
            <td>L3 Name B</td>
        </tr>
        <tr>
            <td rowspan=2>L2 Name B</td>
            <td>L3 Name C</td>
        </tr>
        <tr>
            <td>L3 Name D</td>
        </tr>
    </tbody>
</table>
