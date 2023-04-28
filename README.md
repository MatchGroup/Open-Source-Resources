# Open Source Resources

Resources for open source repositories of Match Group and Match Group brands

## Policy and Process

[Open Sourcing Software at Match Group](https://docs.google.com/document/d/1SGufE9zGKetwrnrRLLjr8P4jBs3uyq4kl44Ay2LEwsM)

## License

All open source repositories ***must*** include a copy of the [LICENSE](https://github.com/MatchGroup/Open-Source-Resources/blob/main/LICENSE) file stored in this repository.

Use the following command to copy the license into the open source repository:

```
curl -O --output-dir <path> https://raw.githubusercontent.com/MatchGroup/Open-Source-Resources/main/LICENSE
```

> Replace `<path>` with the path to the open source repository.

__IMPORTANT AND REQUIRED__

Use the following command to replace `<year-of-publication>` in the copied license to the year that any code included in the project was first publicly available.

```
sed -i '' -e "s/<year-of-publication>/$(date +"%Y")/" <path>/LICENSE
```

> Replace `<path>` with the path to the open source repository.

> The above command will set the year of publication to the current year. Replace `$(date +"%Y")` with a specific year to set it to an earlier year.

## Contribution Policy

All open source repositories ***must*** include the contribution policy.

Copy and paste the following text into the README of the open source repository:

```
## Contributing

While interest in contributing to this project is appreciated, it has been open 
sourced solely for the purpose of sharing with the community. This means we are 
unable to accept outside contributions at this time and pull requests will not 
be reviewed or merged. To report a security concern or vulnerability, please 
submit a GitHub issue.
```

## Copyrights

Source code contained within open source repositories ***must*** include the following copyright notice at the top of every file.

```
//
//  All Contributions by Match Group
//
//  Copyright © <year-range> <brand> (<legal-entity>)
//
//  Licensed under the Match Group Modified 3-Clause BSD License.
//  See https://github.com/<github-organization>/<repository>/blob/main/LICENSE for license information.
//
```

> Replace `<year-range>`, `<brand>`, `<legal-entity>`, `<github-organization>` and `<repository>` with the correct values. The year range starts the year that any code included in the project was first publicly available, followed by a hyphen (-) and ends with the latest year that new code was added. If the years are the same, for example if this is the first time the code is being open sourced, include only the current year (without a hyphen). For many projects the legal entity will be Match Group, LLC.

Here is a Tinder brand example:

```
//
//  All Contributions by Match Group
//
//  Copyright © 2022-2023 Tinder (Match Group, LLC)
//
//  Licensed under the Match Group Modified 3-Clause BSD License.
//  See https://github.com/Tinder/Example/blob/main/LICENSE for license information.
//
```
