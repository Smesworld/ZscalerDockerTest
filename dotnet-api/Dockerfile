FROM mcr.microsoft.com/dotnet/core/sdk:3.0 as build

# Copy csproj and restore as distinct layers
COPY *.csproj .
RUN dotnet restore
