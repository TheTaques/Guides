<!-- markdownlint-disable MD041-->
??? abstract "Streaming Services - [Click to show/hide]"

    | Custom Format                                                                             |                                     Score                                      | Trash ID                                |
    | ----------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------: | --------------------------------------- |
    | [{{ radarr['cf']['amzn']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#amzn)   |                                       0                                        | {{ radarr['cf']['amzn']['trash_id'] }}  |
    | [{{ radarr['cf']['atvp']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#atvp)   |                                       0                                        | {{ radarr['cf']['atvp']['trash_id'] }}  |
    | [{{ radarr['cf']['bcore']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#bcore) | :warning: {{ radarr['cf']['bcore']['trash_scores']['sqp-1-2160p'] }} :warning: | {{ radarr['cf']['bcore']['trash_id'] }} |
    | [{{ radarr['cf']['crit']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#crit)   |             {{ radarr['cf']['crit']['trash_scores']['default'] }}              | {{ radarr['cf']['crit']['trash_id'] }}  |
    | [{{ radarr['cf']['dsnp']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#dsnp)   |                                       0                                        | {{ radarr['cf']['dsnp']['trash_id'] }}  |
    | [{{ radarr['cf']['hbo']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#hbo)     |                                       0                                        | {{ radarr['cf']['hbo']['trash_id'] }}   |
    | [{{ radarr['cf']['hmax']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#hmax)   |                                       0                                        | {{ radarr['cf']['hmax']['trash_id'] }}  |
    | [{{ radarr['cf']['hulu']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#hulu)   |                                       0                                        | {{ radarr['cf']['hulu']['trash_id'] }}  |
    | [{{ radarr['cf']['it']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#it)       |                                       0                                        | {{ radarr['cf']['it']['trash_id'] }}    |
    | [{{ radarr['cf']['max']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#max)     |                                       0                                        | {{ radarr['cf']['max']['trash_id'] }}   |
    | [{{ radarr['cf']['ma']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#ma)       |              {{ radarr['cf']['ma']['trash_scores']['default'] }}               | {{ radarr['cf']['ma']['trash_id'] }}    |
    | [{{ radarr['cf']['nf']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#nf)       |                                       0                                        | {{ radarr['cf']['nf']['trash_id'] }}    |
    | [{{ radarr['cf']['pmtp']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#pmtp)   |                                       0                                        | {{ radarr['cf']['pmtp']['trash_id'] }}  |
    | [{{ radarr['cf']['pcok']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#pcok)   |                                       0                                        | {{ radarr['cf']['pcok']['trash_id'] }}  |
    | [{{ radarr['cf']['stan']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#stan)   |                                       0                                        | {{ radarr['cf']['stan']['trash_id'] }}  |

    !!! warning "Scores marked with a :warning: warning :warning: are different to those used in the main public guide"

    ---

    Breakdown and Why

    - The reason why these Custom Formats have a score of `0` is because they are mainly used for the naming scheme and other variables should decide for movies if a certain release if preferred.
    - `CRiT` and `MA` are the only ones with a positive score because of their better source material, or higher bitrate and quality compared to other streaming services. `BCore` has a negative score as these releases have a very high bitrate so can cause transcoding.
<!-- markdownlint-enable MD041-->
